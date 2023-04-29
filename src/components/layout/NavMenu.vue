<script setup>
const navItems = ['Home', 'About Us', 'Contact']
</script>

<template>
  <header
    class="w-full h-[75px] fixed top-0 bg-purple/70 z-50 flex items-center backdrop-blur-md text-white px-2"
  >
    <div class="container mx-auto flex justify-between items-center">
      <div class="aspect-square w-[50px] bg-orange rounded-full"></div>
      <nav class="hidden md:flex items-center gap-6">
        <ul class="flex gap-6">
          <li
            v-for="item of navItems"
            :key="item"
            class="border-b hover:border-white cursor-pointer border-transparent"
          >
            {{ item }}
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>
