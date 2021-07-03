<template>
  <footer class="col-12">
    <div class="col-12 container-fluid d-flex py-2 gap-2 text-light">
        <div class="col-4 text-center py-3">
            <img :src="'./images/logo.png'" alt="..." class="logo w-75" />
        </div>
        <div class="col-3">Hello</div>
        <div class="col-4">Hello</div>
    </div>
    <div class="col-12 footer-copy py-2 container-fluid text-center">
        Copyright {{new Date().getFullYear()}} © <span style="font-weight: bold;">NOSHISTONE</span>. All Rights Reserved. Designed and developed by Bug Apocalypse
    </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style scoped>
.logo {
    opacity: 20%;
}

footer {
    background: #000000;
}

.footer-copy {
    position: absolute;
    background: gold;
    font-size: 0.8rem;
}
</style>