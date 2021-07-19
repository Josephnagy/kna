<template>
  <div class="home">
    <home-page-carousel> </home-page-carousel>
  </div>
</template>

<script>
// @ is an alias for src 
import HomePageCarousel from '@/components/HomePageCarousel'; 

export default {
  name: "Home", 
  components: {
    HomePageCarousel
  }
};
</script>
