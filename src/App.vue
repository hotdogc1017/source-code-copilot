<script setup lang="ts">
import { ref } from "vue";

const msg = ref("Hello world");
</script>

<template>
  <div>
    <h1>{{ msg }}</h1>
    <input class="border-x-slate-200 rounded-md" v-model="msg" />
  </div>
</template>

<style scoped></style>
