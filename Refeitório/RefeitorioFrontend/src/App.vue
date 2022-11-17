<script setup>
import { RouterView } from "vue-router";
import HeaderComp from "./components/headerComp.vue";
// import compFooter from "./components/compFooter.vue";

</script>

<template>
  <HeaderComp />
  <RouterView />
  <footerComp />
  <!-- <compFooter /> -->
</template>

<style >
body {
  background-color: #dddee1;
}
#app {
  width: 100%;
}
</style>
