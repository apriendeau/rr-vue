<script setup>
import Header from '@/components/Header.vue'
</script>

<template>
  <Header/>
  <div class="about">
    <h1>This is an my page</h1>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: auto;
    display: flex;
  }
}
</style>
