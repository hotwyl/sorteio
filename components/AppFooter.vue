<script setup lang="ts">
  import { ref } from 'vue';
  const year = ref(new Date().getFullYear());

</script>

<template>

  <section class="footer">
    <p>Feito com ♥ por hotwyl | Sistema de Sorteio Online &reg; Todos os direitos reservados | &copy;
      <a href="" target="_blank">WILLFROMBRASIL</a>™ Company Inc <span>{{ year }}</span></p>
  </section>

</template>

<style scoped>

    .footer {
      background-color: #333;
      color: white;
      padding: 1rem;
      text-align: center;
      position: fixed;
      bottom:0;
      width: 100%;
    }

    .footer p {
      margin: 0 auto;
    }

    .footer a {
      color: white;
      text-decoration: none;
    }

</style>