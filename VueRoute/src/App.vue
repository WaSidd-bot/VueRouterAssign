<script setup>
import genresComp from './components/genres.vue'
import headerComp from './components/header.vue'
import footerComp from './components/footer.vue'
import heroComp from './components/hero.vue'
import featureComp from './components/feature.vue'
import detailsComp from './components/details.vue'
</script>

<template>
  <headerComp />
  <heroComp />
  <featureComp />
  <footerComp />
</template>

<style>
body {
    background-color: rgba(7, 5, 27, 0.866);
    position: static;
    color: white;
    margin: 0;
    padding: 0;
}
</style>
