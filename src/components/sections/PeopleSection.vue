<script setup>
import ProfilePic from '../shared/ProfilePic.vue'
</script>

<template>
  <section class="greetings bg-[url('people-bg.png')] min-h-[70vh]">
    <div class="container mx-auto text-center py-40 flex flex-col items-center">
      <h2 class="text-5xl font-bold">Lorem ipsum dolor.</h2>
      <p class="text-xl mt-10 mb-20 max-w-[60ch] text-grey">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium, ratione culpa. Magnam
        veritatis aperiam.
      </p>
      <div class="flex md:flex-row flex-col gap-10 md:gap-52">
        <ProfilePic
          img="https://randomuser.me/api/portraits/women/9.jpg"
          name="Tiffany Castillo"
          v-for="i in 3"
          :key="i"
        />
      </div>
      <div class="flex md:flex-row flex-col gap-10 md:gap-52 my-10">
        <ProfilePic
          img="https://randomuser.me/api/portraits/women/9.jpg"
          name="Tiffany Castillo"
          v-for="i in 2"
          :key="i"
        />
      </div>
    </div>
  </section>
</template>

<style scoped></style>
