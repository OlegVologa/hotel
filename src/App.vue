<script setup>
import MainHeader from './components/MainHeader.vue'
import MainFooter from './components/MainFooter.vue'
import MainCarousel from './components/MainCarousel.vue'
import AboutCompany from './components/AboutCompany.vue'
import MainTasks from './components/MainTasks.vue'
import OurProjects from './components/OurProjects.vue'
import ContactUs from './components/ContactUs.vue'
</script>

<template>
  <div>
    <div class="container">
      <MainHeader />
      <MainCarousel />
      <AboutCompany />
      <MainTasks />
      <OurProjects />
      <ContactUs />
    </div>
    <MainFooter />
  </div>
</template>

<style scoped>
.container {
  max-width: 1440px;
  padding: 0 135px;
}
</style>
