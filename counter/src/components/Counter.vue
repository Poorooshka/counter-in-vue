<script setup>
import { ref } from "vue";

const count = ref(0);
</script>

<template>
  <h1>{{ count }}</h1>
  <button @click="count++">Plus +</button>
  <button @click="count--">Minus -</button>
</template>

<style scoped>
button {
  margin: 1rem;
}
</style>
