<template>
  <!-- <div class="home"> -->
    <HeroSection />
    <Incentives />
    <Features />
    <div class="h-screen bg-dpbm-blue"></div>
    <Quote />
  <!-- </div> -->
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import HeroSection from '../components/HeroSection.vue'
import Incentives from '../components/Incentives.vue'
import Features from '../components/Features.vue'
import Quote from '../components/Quote.vue'

export default {
  name: 'Home',
  components: {
    HeroSection,
    Incentives,
    Features,
    Quote
  }
}
</script>
