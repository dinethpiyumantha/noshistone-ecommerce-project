<template>
  <a-card :loading="loading" :hoverable="true" size="small" class="my-2">

    <img slot="cover" style="width: 250px" alt="example" :src="'./images/Slider/1.jpg'" />

    <template slot="actions" class="ant-card-actions">
      <a-icon v-if="wish" key="wish" type="heart" theme="filled" style="color: gold; font-size: 1.5rem;" v-on:click="wishUpdater()"/>
      <a-icon v-if="!wish" key="wish" type="heart" theme="outlined" style="font-size: 1.5rem;" v-on:click="wishUpdater()"/>
      <a-icon key="share" type="share-alt" style="font-size: 1.5rem;" />

      <a-popover placement="bottomRight">
        <template slot="content">
          <p>Content</p>
          <p>Content</p>
        </template>
        <template slot="title">
          <span>Title</span>
        </template>
        <a-button style="border: 0px; background: none;">
            <a-icon key="ellipsis" type="ellipsis" style="font-size: 1.5rem;" />
        </a-button>
      </a-popover>
      
    </template>
    <a-card-meta title="Card title" description="This is the description">
    </a-card-meta>
  </a-card>
</template>

<script>
export default {
    data() {
        return (
            {
                wish: false,
                loading: true,
            }
        );
    },
    created() {
        setTimeout(this.loadingUpdater, 5000);
    },
    methods: {
        wishUpdater() {
            this.wish = (this.wish) ? false : true;
        },
        loadingUpdater() {
            this.loading = false;
        }
    }
};
</script>

<style scoped>
</style>