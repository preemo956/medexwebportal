<script setup>
import NavMenu from '@/components/NavMenu.vue'
import MainCards from './components/MainCards.vue';
import HomePage from './components/HomePage.vue';
import MainPagination from './components/MainPagination.vue';
</script>

<template>
  <NavMenu />
  <HomePage />
  <RouterView />
  <div class="wrapper">
    <MainCards />
    <MainPagination />



  </div>
</template>

<style scoped lang="postcss">
.wrapper {
  @apply container mx-auto flex flex-col gap-4 py-4;
}
</style>
