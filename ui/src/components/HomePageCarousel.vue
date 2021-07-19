<template>
  <div>
    <h1> Image Carousel</h1>
      
    <b-carousel
        id="home-page-carousel"
        :interval="4000"
        controls
        indicators
        img-width="1024"
        img-height="480"
        style="text-shadow: 1px 1px 2px #333;"
    >
        <b-carousel-slide
        caption="First slide"
        img-src="https://picsum.photos/1024/480/?image=52"
      ></b-carousel-slide>
      <b-carousel-slide
        caption="Second slide"
        img-src="https://picsum.photos/1024/480/?image=54"
      ></b-carousel-slide>


    </b-carousel>
  </div>
</template>

<script> 
export default {
  name: 'HomePageCarousel'
}
</script> 