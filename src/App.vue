<template>

  <Navbar />
  <!-- if I don't sent any props it will take default value 
  title="testing " subTitle="testing para"
  -->
  <Hero />
<HomeCard/>

</template>
<script setup>
import Navbar from './components/Navbar.vue'
import Hero from './components/Hero.vue'
import HomeCard from './components/HomeCard.vue'
</script>
<style scoped></style>
