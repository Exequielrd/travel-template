<script setup>
import SimpleCard from '../shared/SimpleCard.vue'
</script>

<template>
  <section class="relative container mx-auto h-screen">
    <div class="flex gap-5 justify-center z-30 absolute top-[-200px] left-1/2 right-1/2">
      <SimpleCard />
      <SimpleCard />
      <SimpleCard />
    </div>
    <h2 class="text-5xl text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit.</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, ratione culpa. Magnam
      veritatis aperiam odio, a beatae illo voluptatum neque.
    </p>
  </section>
</template>

<style scoped></style>
