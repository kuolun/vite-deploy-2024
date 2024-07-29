<script setup>
import { ref } from 'vue'
let num = ref(0)
</script>

<template>
  <div>
    <span>{{ num }}</span>
    <button @click="num++">Increment</button>
  </div>
</template>

<style scoped></style>
