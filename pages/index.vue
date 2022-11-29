<template>
  <h1 class="font-bold text-5xl mb-10">Hello, Mastering Nuxt 3!</h1>
  <NuxtLink
    class="rounded text-white font-bold py-2 px-4 cursor-pointer bg-green-500"
    :href="firstLesson.path"
  >
    Go to first lesson
  </NuxtLink>
</template>

<script setup lang="ts">
const firstLesson = useFirstLesson();
</script>

<style scoped></style>
