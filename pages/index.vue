<template>
  <div>
    <h1>Welcome to the homepage</h1>
    <AppAlert>
      This is an auto-imported component
    </AppAlert>
  </div>
</template>

<script setup lang="ts">
  // importar e definir layout personalizado para esta pagina
  import { defineComponent } from 'vue';
  import AppAlert from '~/components/AppAlert.vue';

  defineComponent({
    name: 'HomePage',
    layout: 'default',
  });

</script>