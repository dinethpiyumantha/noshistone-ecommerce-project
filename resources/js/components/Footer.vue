<template>
  <footer class="col-12">
    <div class="col-12 container-fluid d-flex py-2 gap-2 text-light">
        <div class="col-4 text-center py-3">
            <img :src="'./images/logo.png'" alt="..." class="logo w-75" />
        </div>
        <div class="col-3 py-2">
            <p style="font-size: 0.9rem;">Link</p>
        </div>
        <div class="col-4 py-2">
            <p style="font-size: 0.9rem;">A journey of a thousand miles begins with a fabulous pair. Grab your pair. DM for inquiries | island wide delivery available (conditions applied).</p>
            <div style="font-size: 2rem;">
                <span><i class="fab fa-facebook-square"></i></span>
                <span><i class="fab fa-instagram"></i></span>
            </div>
        </div>
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

.social-btns {
    font-size: 2rem;
}
</style>