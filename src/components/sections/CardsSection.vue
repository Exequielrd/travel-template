<script setup>
import PersonCard from '../shared/PersonCard.vue'
import CTA from '../shared/CallToAction.vue'
</script>

<template>
  <div class="w-full min-h-[70vh] flex flex-col justify-center items-center">
    <h2 class="text-4xl font-bold text-center">Lorem ipsum dolor.</h2>
    <p class="text-center text-lg mt-5 mb-14 max-w-[65ch]">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, ratione culpa. Magnam
      veritatis aperiam
    </p>
    <div class="flex gap-5">
      <PersonCard v-for="i of 3" :key="i" />
    </div>
    <CTA class="mt-10" />
  </div>
</template>
