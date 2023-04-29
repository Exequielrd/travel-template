<script setup>
import SimpleCard from '../shared/SimpleCard.vue'
import ImageCard from '../shared/ImageCard.vue'
import CallToAction from '../shared/CallToAction.vue'
import bgImage1 from '/src/assets/card-image-1.png'
import bgImage2 from '/src/assets/card-image-2.png'
</script>

<template>
  <section class="relative container mx-auto flex flex-col items-center">
    <div
      class="grid grid-cols-1 md:grid-cols-2 lg:flex lg:absolute gap-5 justify-center z-30 top-[-200px] left-1/2 right-1/2"
    >
      <SimpleCard v-for="i in 3" :key="i" />
    </div>
    <h2 class="text-5xl text-center max-w-[35ch] mt-28">
      Lorem ipsum dolor sit amet consectetur adipisicing elit.
    </h2>
    <p class="max-w-[65ch] text-center my-8 text-grey text-xl">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, ratione culpa. Magnam
      veritatis aperiam odio, a beatae illo voluptatum neque.
    </p>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-5 my-10">
      <div class="flex flex-col gap-5">
        <ImageCard :bg="bgImage1" />
        <ImageCard height="350px" :bg="bgImage2" />
      </div>
      <div class="flex flex-col gap-5">
        <ImageCard height="350px" :bg="bgImage2" />
        <ImageCard :bg="bgImage1" />
      </div>
      <div class="flex flex-col gap-5">
        <ImageCard :bg="bgImage1" />
        <ImageCard height="350px" :bg="bgImage2" />
      </div>
    </div>
    <CallToAction />
  </section>
</template>
