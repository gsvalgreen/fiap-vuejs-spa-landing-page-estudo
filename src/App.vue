<template>
  <div id="app">
    <Header logoText="LP do Gustavo" />
    <router-view />
    <Footer />
  </div>
</template>

<script setup>
import Header from './components/Header.vue'
import Footer from './components/Footer.vue'
</script>
