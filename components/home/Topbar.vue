<template>
  <header>
    <div class="flex justify-between items-center max-w-7xl mx-auto p-4">
      <div class="__site_logo flex items-center">
        <img src="/public/favicon.ico" alt="logo" />
        <h1 class="text-md font-semibold ml-2">ATrade</h1>
      </div>
      <div class="site_menu  absolute trasnform -translate-x-1/2 left-1/2">
        <div class="flex menu__list space-x-5">
          <div class="menu__item">
            Tutorials
          </div>
          <div class="menu__item">
            Market Trends
          </div>
          <div class="menu__item">
            Investments Strategies
          </div>
        </div>
      </div>
      <div class="search-box">
        <div class="search-box__input-wrapper relative">
          <Icon name="uil:search"
            class="search-box__icon absolute top-1/2 left-3 transform -translate-y-1/2 text-gray-400" />
          <input type="text" placeholder="Search..." autocomplete="off"
            class="search-box__input border outline-none py-2 pl-10 pr-4 rounded-full w-full text-gray-400"
            aria-label="Search" />
        </div>
      </div>
    </div>
  </header>
</template>
<script setup lang="ts">
</script>