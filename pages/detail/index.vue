<script setup lang="ts">
definePageMeta({
  layout: 'home'
})
</script>

<template>
  <main class="container max-w-7xl mx-auto p-4">
    <div class="grid grid-cols-7 gap-10">
      <div class="col-span-5 content">
        <h2 class="content__title font-semibold text-3xl mb-3">Understanding Market Volatility: A Comprehensive
          Guide</h2>

        <div class="author_detail flex gap-3 items-center">
          <img src="https://picsum.photos/200" alt="" class="rounded-full w-10 h-10 border">
          <div class="author_detail__name flex flex-col">
            <span class="font-semibold">Atrader</span>
            <small>March 15, 2025</small>
          </div>
        </div>


        <img src="https://picsum.photos/200" alt="" class="w-full max-h-96 border rounded-md mt-5">

        <div class="content__body mt-5">
          <p>
            <span>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Exercitationem harum magnam repellendus voluptatibus. Architecto distinctio eligendi, et id labore libero modi non nostrum numquam quos reprehenderit saepe temporibus unde vitae?</span><span>Aperiam asperiores eius natus nostrum odit perferendis quis? Accusantium aspernatur aut, beatae culpa eaque est eveniet fugit harum illo incidunt inventore itaque nemo porro provident quibusdam, quisquam quod repellat ut!</span><span>Architecto numquam soluta veritatis. Debitis dicta eveniet, excepturi facere molestias quis reiciendis unde. Accusantium aliquid aspernatur eius, eos, harum optio placeat quidem quos sequi sit tempore voluptatum! Fugiat, repudiandae, voluptate.</span><span>Aut, cupiditate debitis deserunt ea facilis quaerat quod quos sapiente. Ab architecto, assumenda atque cupiditate doloribus eaque esse modi, natus odio praesentium, quia quidem rerum sit soluta tempore. Eligendi, quos!</span><span>Accusamus eos hic nemo odio! Eos eveniet, odit. Ab accusamus aspernatur dolorum fugit impedit maiores molestias nemo, nostrum quisquam quos reiciendis repudiandae unde vel. Deserunt id nisi repellat sed totam.</span><span>A aspernatur excepturi maxime odio sed sequi voluptatem? Debitis distinctio eius eligendi enim facere fuga ipsa, ipsum labore laboriosam magni minus neque pariatur placeat quas repellendus sed ut vitae, voluptate!</span><span>Nisi placeat possimus praesentium sunt voluptates? Blanditiis eius eos impedit, magnam nostrum quibusdam repudiandae sequi sint. Autem ea laboriosam optio porro tempore. Autem, consectetur impedit incidunt iure magni vero voluptate.</span><span>Laborum maiores quo tempora tenetur voluptas. Accusamus aliquid atque beatae doloribus eius exercitationem hic id illum ipsum minus neque odio quo, tempore ut veniam veritatis voluptates? Ex illo iure ratione!</span><span>A alias aliquid blanditiis culpa enim, excepturi hic ipsa ipsam ipsum laborum magni maiores, necessitatibus nemo nihil nostrum quasi rem repellendus sapiente sed soluta tempora totam vel voluptas. Culpa, fuga.</span><span>A ab ad alias, amet architecto assumenda atque dignissimos error esse est impedit inventore laboriosam modi mollitia officia perferendis praesentium quasi quia quis recusandae rem sequi soluta, sunt veniam voluptatum?</span>
          </p>
        </div>

      </div>

      <div class="col-span-2">
        <ArticleAuthorDetail/>

        <!--        related article-->
        <ArticleRelatedArticle/>

      </div>
    </div>
  </main>
</template>

<style scoped lang="scss">

</style>