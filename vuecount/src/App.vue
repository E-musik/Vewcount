<script setup>
import { ref } from 'vue'
const count = ref(0)
</script>

<template>
  <div>
    <h4>The current count = </h4>
    <h1>{{count}}</h1>
    <button @click="count++">+</button>
    <button @click="count--">-</button>

  </div>
</template>

<style scoped>
button {
  font-weight: bold;
}
h1{
  color: blue;
}
</style>
