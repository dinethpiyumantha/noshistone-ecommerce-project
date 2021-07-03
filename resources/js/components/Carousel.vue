<template>
  <Carousel 
    :perPageCustom="[[0, 1], [1024, 2]]"
    :autoPlay="true"
    :autoplayTimeout="2000"
    :paginationColor="'#000000'"
    :paginationActiveColor="'#F4B71A'"
    :paginationPadding="5"
    :paginationSize="15"
    :easing="'ease'"
    >
    <Slide>
        <img class="col-12" src="images/Slider/s1.jpg" alt="..." />
    </Slide>
    <Slide>
        <img class="col-12" src="images/Slider/s1.jpg" alt="..." />
    </Slide>
    <Slide>
        <img class="col-12" src="images/Slider/s1.jpg" alt="..." />
    </Slide>
    <Slide>
        <img class="col-12" src="images/Slider/s1.jpg" alt="..." />
    </Slide>
    <Slide>
        <img class="col-12" src="images/Slider/s1.jpg" alt="..." />
    </Slide>
    <Slide>
        <img class="col-12" src="images/Slider/s1.jpg" alt="..." />
    </Slide>
  </Carousel>
</template>

<script>
import { Carousel, Slide } from "vue-carousel";

export default {
  components: {
    Carousel,
    Slide,
  },
};
</script>

<style>
</style>