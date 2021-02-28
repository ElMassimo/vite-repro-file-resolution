<template>
  <h1>Vite Ruby assets issue</h1>
  <HelloWorld msg="Counter component" />
  <br>
  <img src="./images/logo.png" alt="Vue logo">
  <img src="@/images/logo.png" alt="Vue logo @ alias">
  <img :src="vueLogo" alt="Vue logo import">
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'
import vueLogo from './images/logo.png'
</script>