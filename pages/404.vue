<template>
  <h1 class="font-bold text-gray-700 text-9xl mb-10">404</h1>
  <p class="text-3xl mb-10">I guess that page doesn't exist.</p>
  <NuxtLink
      class="rounded text-white font-bold py-2 px-4 cursor-pointer bg-green-500"
      to='/'
  >
    Go back Home
  </NuxtLink>
</template>

<script setup>
definePageMeta({
  layout: '404'
})
</script>
