<script setup>
import { RouterView } from 'vue-router'
import Menu from './components/MenuCompact.vue'
import Footer from './components/Footer.vue'
</script>

<template>
  <Menu />
  <main>
    <RouterView />
  </main>
  <Footer />
</template>

<style scoped>

</style>
