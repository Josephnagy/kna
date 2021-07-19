<template>
  <div class="home">
    
    <!-- Image Carousel -->
    <home-page-carousel> </home-page-carousel>
  </div>
</template>

<script>
// @ is an alias to /src
import HomePageCarousel from '@/components/HomePageCarousel.vue'

export default {
  name: 'Home', 
  components: {
    HomePageCarousel
  }
}
</script>
