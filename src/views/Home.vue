<template>
  <div class="home">
    <div class="carousel">
      <VueSlickCarousel v-bind="settings">
        <div>
          <img src="https://cloudfront-us-east-1.images.arcpublishing.com/gmg/EJ3RCR557JETPCJKNI4R2PWSPI.jpg" alt="" />
        </div>
        <div><img src="https://ak.picdn.net/shutterstock/videos/1026819017/thumb/11.jpg" alt="" /></div>
        <div><img src="https://i.pinimg.com/236x/d4/ac/4f/d4ac4f82a508dfe8d162c3c1bbb697da.jpg" alt="" /></div>
        <div><img src="https://i.redd.it/rio9i77fdyg61.jpg" alt="" /></div>
        <div>
          <img
            src="https://warrington.ufl.edu/entrepreneurship-and-innovation-center/wp-content/uploads/sites/113/2018/02/baby-gator-in-hand-16x9-960x541.jpg"
            alt=""
          />
        </div>
        <div>
          <img
            src="https://bloximages.newyork1.vip.townnews.com/postandcourier.com/content/tncms/assets/v3/editorial/1/d3/1d3f4418-8fc6-11ea-a6c6-f310c205578d/5b16added178f.image.jpg?resize=1200%2C707"
            alt=""
          />
        </div>
      </VueSlickCarousel>
    </div>
  </div>
</template>

<style>
.carousel {
  background: #2d5000;
  max-width: 70%;
  margin: auto;
  padding: 50px;
}
</style>

<script>
// import $ from "jquery";
import VueSlickCarousel from "vue-slick-carousel";
import "vue-slick-carousel/dist/vue-slick-carousel.css";
import "vue-slick-carousel/dist/vue-slick-carousel-theme.css";
export default {
  data: function () {
    return {
      settings: {
        arrows: true,
        dots: true,
        dotsClass: "slick-dots",
        centerMode: true,
        edgeFriction: 0.75,
        infinite: true,
        speed: 150,
        slidesToShow: 1,
        slidesToScroll: 1,
        autoplay: true,
        pauseOnDotsHover: true,
        focusOnSelect: true,
        adaptiveHeight: true,
        variableWidth: true,
        fade: false,
      },
    };
  },
  name: "MyComponent",
  components: { VueSlickCarousel },
  methods: {},
};
</script>
