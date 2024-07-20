<template>
  <v-app>
    <v-main>
      <ApplicationBar/>
      <AppCarousel />
      <AboutStudio01/>
      <AboutStudio02/>
      <AboutStudio03/>
    </v-main>

    <AppFooter />
  </v-app>
</template>

<script setup>
import ApplicationBar from '../components/ApplicationBar.vue'
import AppCarousel from '../components/AppCarousel.vue'
import AboutStudio01 from '../components/AboutStudio01.vue'
import AboutStudio02 from '../components/AboutStudio02.vue'
import AboutStudio03 from '../components/AboutStudio03.vue'
</script>
<style>
   .title-size{
    font-size: 13px;
  }
</style>
