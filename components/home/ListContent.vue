<template>
  <div class="article_card border rounded-lg" v-for="i in 4" :key="i">
    <div class="card__header">
      <div class="container w-full h-52 bg-gray-700 rounded-lg grid place-content-center text-white">
        Article Image
      </div>
    </div>
    <div class="card__body p-3">
      <span class="font-semibold text-xl mb-3 block">Understanding Market Volatility</span>
      <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium architect</p>
      <button class="font-semibold mt-3 flex items-center">Read More
        <Icon name="uil:arrow-right"/>
      </button>
    </div>
  </div>
</template>