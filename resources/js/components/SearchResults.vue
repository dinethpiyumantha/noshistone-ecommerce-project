<template>
  <div class="container my-3">
    <div class="col-12">
      <input
        v-model="search"
        class="form-control"
        type="text"
        placeholder="Search Footwares"
      />
    </div>
    <h5 class="my-3" v-if="searchInput">Results for '{{ search }}'</h5>
    <div class="col-12 my-2 py-1">
        Result
    </div>
  </div>
</template>

<script>
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
};
</script>

<style>
</style>