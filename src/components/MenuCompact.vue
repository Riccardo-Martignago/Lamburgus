<script setup>
import { RouterLink } from 'vue-router'
</script>

<template>
  <section class="flex justify-between p-8 text-3xl">

    <nav class="flex">
      <div class="logo">
        <img src="/LAMBURGUS logo.png" alt="Lamburgus">
      </div>
      <ul class="flex">
        <li><RouterLink to="/">Home</RouterLink></li>
        <li><RouterLink to="/about">About</RouterLink></li>
      </ul>
    </nav>
    <div class="c-butt">
      <button class="my_b-login">
        Login
      </button>
    </div>
  </section>
</template>

<style scoped>
  section{
    position: fixed;
    left: 0;
    right: 0;
    background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.1));
    color: #f8f8dc;
  }
  div > img {
    width: 50px;
    height: 50px;
  }
  ul li, .c-butt{
    display: inline-block;
    margin:auto 0;
    padding: 0 30px;
  }
</style>
