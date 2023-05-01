<script setup>
import CallToAction from '../shared/CallToAction.vue'
</script>

<template>
  <footer class="bg-purple pt-20 pb-10 px-5 text-white flex flex-col items-center">
    <div class="container">
      <div class="flex gap-5 items-center justify-center">
        <div class="aspect-square bg-orange w-[30px] rounded-full"></div>
        <h2 class="text-xl font-light">Travel Template</h2>
      </div>
      <ul class="flex mt-8 gap-10 text-center font-bold text-grey justify-center">
        <li>Home</li>
        <li>About us</li>
        <li>Contact</li>
      </ul>
      <div class="flex justify-between w-full mt-10">
        <CallToAction />
        <span class="text-md"> made by @exequielrd </span>
      </div>
    </div>
  </footer>
</template>
