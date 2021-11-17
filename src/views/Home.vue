<template>
  <!-- <div class="home"> -->
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <HeroSection />
    <Incentives />
  <!-- </div> -->
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeroSection from '../components/HeroSection.vue'
import Incentives from '../components/Incentives.vue'

export default {
  name: 'Home',
  components: {
    HeroSection,
    Incentives
  }
}
</script>
