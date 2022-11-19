<template>
  <header>
    <h1>{{title}}</h1>
  </header>
  <main>
  </main>
</template>
<script setup>
import TheWelcome from '../components/TheWelcome.vue'
const { createApp } = Vue;
  createApp({
    data() {
      return {
        title : 'Chtulu'
      }
    },
  })
</script>
