<template>
  <div>
    <NavBar />
    <div class="col-12 py-1" style="background: #000;"></div>
    <Carousel />
    <SearchResults />
    <Footer />
  </div>
</template> 

<script>
import NotificationBar from "./NotificationBar.vue";
import NavBar from "./NavBar.vue";
import Carousel from "./Carousel.vue";
import SearchResults from "./SearchResults.vue";
import Footer from "./Footer.vue";

export default {
  components: {
    NotificationBar,
    NavBar,
    Carousel,
    SearchResults,
    Footer,
  },
};
</script>

<style>
</style>