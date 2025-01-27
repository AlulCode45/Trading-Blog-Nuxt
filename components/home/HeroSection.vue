<template>
  <div class="hero_section containerp-4 py-10 h-screen bg-gray-50">
    <div class="hero_section__content flex gap-10 items-center w-full  max-w-7xl mx-auto ">
      <div class="hero_content__left">
        <h2 class="text-4xl font-bold mb-3">Master the Art of Trading</h2>
        <p class="mb-5">
          Expert insights, strategies, and tutorials to help you succeed in the financial markets.
        </p>
        <button
            class="px-7 py-2 text-white bg-black rounded-md hover:bg-gradient-to-br hover:from-black hover:to-green-400 hover:shadow-lg transition-all duration-300 ease-in hover:scale-105 ">
          Start Learning
        </button>
      </div>
      <div class="hero_content__right w-1/2">
        <div class="bg-gray-700 rounded-lg w-full h-[450px] text-white">
          <WidgetTradingView/>
        </div>
      </div>
    </div>
  </div>
</template>