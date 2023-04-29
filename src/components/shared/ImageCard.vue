<script setup>
defineProps({
  height: {
    type: String,
    default: '500px'
  },
  bg: {
    type: String,
    required: false
  }
})
</script>
<template>
  <div
    class="rounded-md w-[300px] bg-no-repeat bg-cover p-5 flex flex-col justify-between cursor-pointer hover:scale-105 ease-in-out"
    :style="{ height: height, backgroundImage: `url(${bg})` }"
  >
    <div>
      <h2 class="text-2xl font-bold capitalize">Lorem ipsum</h2>
      <p class="text-grey text-lg mt-2">Lorem ipsum dolor sit amet consectetur</p>
    </div>
    <div class="flex gap-2 items-center">
      <div class="w-[40px] aspect-square bg-grey rounded-full"></div>
      <div>
        <p class="text-white text-md font-bold">Lorem ipsum</p>
        <p class="text-grey text-sm">Lorem ipsum</p>
      </div>
    </div>
  </div>
</template>
