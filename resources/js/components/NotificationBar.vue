<template>
  <div class="bar col-12 py-0 text-center">
      <small><b>Noshistone</b> Version 0.01 (2021)</small>
  </div>
</template>

<script>
export default {

}
</script>

<style>
small {
    color: #35495e;
}

.bar {
    background: #41b782;
    height: 0px;
    padding: 0px;
    overflow: hidden;
    box-sizing: border-box;
    animation-name: hideanim;
    animation-duration: 4s;
    animation-iteration-count: unset;
}

@keyframes hideanim {
    0% {
        height: 0px;
        padding: 0px;
    }
    20% {
        height: 30px;
        padding: 5px;
    }
    80% {
        height: 30px;
        padding: 5px;
    }
    100% {
        height: 0px;
        padding: 0px;
    }
}
</style>