<template>
  <div class="p-12">
    <h1 class="font-bold text-2xl mb-10">Hello, Mastering Nuxt 3!</h1>
    <NuxtLink
        class="rounded text-white font-bold py-2 px-4 cursor-pointer bg-green-500"
        to='/course'
    >
      Go to Courses
    </NuxtLink>
  </div>
</template>

<script>
export default {
  name: "Home"
}
</script>

<style scoped>

</style>
