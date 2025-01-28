<script setup lang="ts">

</script>

<template>
  <div class="related__article bg-gray-50 rounded-md p-5 mt-5">
    <h3 class="font-semibold text-lg mb-3">Related Articles</h3>
    <div class="grid grid-cols-1 gap-2">
      <div class="article_list flex gap-3 items-center" v-for="i in 4">
        <img src="https://picsum.photos/200/300" alt="" class="w-24 h-24 rounded-md border">
        <div class="article__detail">
          <div class="article_title flex flex-col gap-1">
            <span class="font-semibold text-sm">Cryptocurrency on the future</span>
            <small class="text-xs">March 24, 2025</small>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped lang="scss">

</style>