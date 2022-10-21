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
  background-color: #DDDEE1;
}
</style>
