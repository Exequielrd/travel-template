<script setup>
import NavMenu from './components/layout/NavMenu.vue'
import Footer from './components/layout/FooterSection.vue'
import HeroSection from './components/sections/HeroSection.vue'
import GridSection from './components/sections/GridSection.vue'
import PeopleSection from './components/sections/PeopleSection.vue'
import CardsSection from './components/sections/CardsSection.vue'
</script>

<template>
  <NavMenu />
  <main class="bg-purple text-white px-3">
    <HeroSection />
    <GridSection />
    <PeopleSection />
    <CardsSection />
  </main>
  <Footer />
</template>

<style></style>
