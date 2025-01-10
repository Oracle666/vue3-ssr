<script setup lang="ts">
import { ref } from 'vue';
const a = ref<number>(0)

</script>

<template>
  <main>
    <h1 @click="a++">{{ a }}</h1>
    <div>111122213</div>
  </main>
</template>