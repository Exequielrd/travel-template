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
      <h2 class="text-2xl font-bold">Lorem ipsum</h2>
      <p class="text-grey text-xl my-5">Lorem ipsum dolor sit amet consectetur</p>
    </div>

    <div>
      <p class="text-grey text-xl my-5">Lorem ipsum</p>
    </div>
  </div>
</template>
