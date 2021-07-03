<template>
  <div>
    <NavBar />
    <Carousel />
    <Footer />
  </div>
</template>

<script>
import NavBar from "./NavBar.vue";
import Carousel from "./Carousel.vue";
import Footer from "./Footer.vue";

export default {
  components: {
    NavBar,
    Carousel,
    Footer,
  },
};
</script>

<style>
</style>