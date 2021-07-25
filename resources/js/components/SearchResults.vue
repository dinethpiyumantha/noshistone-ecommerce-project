<template>
  <div class="container my-3">
    <div class="col-12">
      <a-input-search
        v-model="search"
        placeholder="Search Footwares"
        class="w-100 py-2"
        @search="onSearch"
      />
    </div>

    <div class="row">
      <div class="col-3 my-2">
        <a-card title="Default size card"> </a-card>
      </div>
      <div class="col-9">
        <h5 class="my-3" v-if="searchInput">Results for '{{ search }}'</h5>
        <div class="col-12 my-2 py-1 d-flex justify-content-around flex-wrap">
          <Card />
          <Card />
          <Card />
          <Card />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Card from "./Card.vue";

export default {
  data() {
    return {
      search: "",
    };
  },
  computed: {
    searchInput() {
      return this.search == "" ? false : true;
    },
  },
  components: {
    Card,
  },
  methods: {},
};
</script>

<style>
</style>