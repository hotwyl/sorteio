<script setup lang="ts">

</script>

<template>

  <section class="header">
    <nav>
      <ul>
        <li>
          <nuxt-link to="/">Home</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/about">About</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/numbers">Sorteio Numeros</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/names">Sorteio Nomes</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/sequence">Sorteio Sequencia</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/members_team">Sorteio Membros</nuxt-link>
        </li>
        <li>
          <nuxt-link to="/themes_squad">Sorteio Temas</nuxt-link>
        </li>
      </ul>
    </nav>
  </section>

</template>

<style scoped>

  .header {
    background-color: #333;
    color: white;
    padding: 1rem;
    text-align: center;
  }

  nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
    padding: 0;
  }

  nav ul li {
    margin: 0 1rem;
  }

  nav ul li a {
    color: white;
    text-decoration: none;
  }

  nav ul li a:hover {
    text-decoration: underline;
  }

</style>