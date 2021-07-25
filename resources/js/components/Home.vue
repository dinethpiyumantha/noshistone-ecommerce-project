<template>
  <div>
    <NavBar />
    <div class="col-12 py-1" style="background: #000;"></div>
    <!-- <Carousel /> -->
    <CarouselMain />
    <SearchResults />
    <Footer />
    <BackToTop />
  </div>
</template> 

<script>
import NotificationBar from "./NotificationBar.vue";
import NavBar from "./NavBar.vue";
import Carousel from "./Carousel.vue";
import SearchResults from "./SearchResults.vue";
import Footer from "./Footer.vue";
import BackToTop from "./BackToTop.vue";
import CarouselMain from "./CarouselMain.vue";

export default {
  components: {
    NotificationBar,
    NavBar,
    Carousel,
    SearchResults,
    Footer,
    BackToTop,
    CarouselMain,
  },
};
</script>

<style>
</style>