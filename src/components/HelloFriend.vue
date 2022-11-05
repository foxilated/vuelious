<script setup lang="ts">
import { ref } from 'vue';

let hello = ref('hello friend.');
</script>
<template>
  <main class="bg-slate-700 min-h-screen flex items-center justify-center">
    <h1 class="text-3xl text-slate-100 font-light animate-pulse">
      {{ hello }}
    </h1>
    <div class="i-ph-moon-stars" />
  </main>
</template>
