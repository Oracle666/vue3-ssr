<script setup lang="ts">
import { ref } from "vue"

const count = ref<number>(0)
</script>

<template>
  <main>
    <h1 @click="count++">{{ count }}</h1>
  </main>
</template>