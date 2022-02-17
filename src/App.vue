<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <RouterView />
</template>

<style lang="less">
  @import "./assets/variables.less";
  body {
    height: auto;
    font-family: 'Open Sans', sans-serif;
    margin: 0;
    background: @white;
  }
</style>
