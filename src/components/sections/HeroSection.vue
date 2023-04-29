<script setup>
import CallToAction from '../shared/CallToAction.vue'
</script>

<template>
  <section class="container mx-auto flex flex-col items-center justify-center min-h-screen">
    <div class="max-w-[800px] text-center z-20">
      <h1 class="text-6xl">Lorem ipsum dolor sit amet consectetur adipisicing elit.</h1>
      <p class="text-grey text-xl py-10">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, ratione culpa. Magnam
        veritatis aperiam odio, a beatae illo voluptatum neque.
      </p>
      <CallToAction></CallToAction>
    </div>
    <img src="/src/assets/hero.jpg" alt="" class="absolute top-0 z-10 opacity-40 h-[90vh] w-full" />
  </section>
</template>
