<script setup>
defineProps({
  img: String,
  name: String
})
</script>

<template>
  <div class="flex flex-col items-center hover:scale-105 cursor-pointer">
    <img :src="img" alt="" class="rounded-full aspect-square w-[75px]" />
    <p>{{ name }}</p>
  </div>
</template>
