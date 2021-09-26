<template>
  <v-app>
    <v-main>
      <v-container>
        <LogoBar></LogoBar>
        <CarCards></CarCards>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import CarCards from './views/CarCards.vue'
export default {
  name: 'App',
  data: () => ({}),

  components: {
    CarCards,
    LogoBar,
  }
};
</script>
