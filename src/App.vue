<script setup lang="ts">
import { ref } from 'vue'

const msg = ref('Hello world')
</script>

<template>
  <div>
    <h1>{{ msg }}</h1>
    <input v-model="msg" class="border-2 border-slate-500 rounded-md">
  </div>
</template>

<style scoped></style>
