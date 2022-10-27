<script setup>
import { RouterView } from "vue-router";
import HeaderComp from "./components/headerComp.vue";
</script>

<template>
  <HeaderComp />
  <RouterView />
</template>

<style>
body {
  background-color: #dddee1;
  width: 100%;
}
#app {
  width: 100%;
}
</style>
