<template>
  <div>
      <Home/>
  </div>
</template>

<script>
import Home from "./components/Home.vue";
export default {
  mounted() {
    console.log("Component mounted.");
  },
  components: {
    Home,
  },
};
</script>

<style>
* {
  /* font-family: 'Poppins', sans-serif; */
  /* font-family: 'Roboto', sans-serif; */
  font-family: 'Open Sans', sans-serif;
}
</style>