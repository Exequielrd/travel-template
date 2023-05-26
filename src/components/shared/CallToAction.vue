<script setup>
defineProps({
  outlined: Boolean
})
</script>
<template>
  <button
    class="w-[250px] h-[50px] bg-orange/90 hover:bg-orange rounded-lg"
    :class="{
      'bg-transparent border border-orange hover:bg-orange text-orange/80 hover:text-white':
        outlined
    }"
  >
    <slot>Call to action</slot>
  </button>
</template>
