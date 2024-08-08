<template>

  <div>

    <header><AppHeader /></header>

    <main><slot /></main>

    <footer><AppFooter /></footer>

  </div>

</template>

<script setup lang="ts">
import AppHeader from "~/components/AppHeader.vue";
import AppFooter from "~/components/AppFooter.vue";
</script>

<style scoped>
 main {
   max-width: 90vw;
   margin: 1vh auto;
 }
</style>