<script setup>
import CallToAction from '../shared/CallToAction.vue'
</script>

<template>
  <footer class="bg-purple py-20 px-5 text-white flex flex-col items-center">
    <div class="container flex flex-col md:flex-row justify-between items-center">
      <div>
        <div class="flex gap-5 items-center mb-5">
          <div class="aspect-square bg-orange w-[30px] rounded-full"></div>
          <h2 class="text-xl font-light">Travel Template</h2>
        </div>
        <CallToAction outlined />
      </div>
      <ul
        class="flex flex-col text-center gap-3 font-semibold text-grey justify-center my-10 md:my-0"
      >
        <li class="cursor-pointer border-b border-transparent hover:border-white">Home</li>
        <li class="cursor-pointer border-b border-transparent hover:border-white">About us</li>
        <li class="cursor-pointer border-b border-transparent hover:border-white">Contact</li>
      </ul>
      <div class="flex justify-between mt-10">
        <span class="text-md">Made by @exequielrd</span>
      </div>
    </div>
  </footer>
</template>
