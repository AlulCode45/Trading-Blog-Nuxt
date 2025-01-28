<script setup lang="ts">
definePageMeta({
  layout: 'home',
})

useHead({
  title: 'Atrade - Platform Belajar Trading',
})

</script>

<template>
  <HomeHeroSection/>
  <div class="grid grid-cols-3 container max-w-7xl mx-auto p-4 mb-20 gap-10">
    <div class="col-span-2">
      <h2 class="text-3xl font-semibold mb-5">Latest Article</h2>
      <div class="grid grid-cols-2 gap-5">
        <HomeListContent v-for="i in 4" :key="i"/>
      </div>
    </div>
    <div class="col-span-1 flex flex-col space-y-5">
      <WidgetCategory/>
      <WidgetNewsLetter/>
    </div>
  </div>
</template>