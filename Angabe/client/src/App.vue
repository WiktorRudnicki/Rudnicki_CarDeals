<template>
  <v-app>
    <v-main>
      <v-container class="d-flex flex-wrap">
        <LogoBar style="width: 100% height: 5%"></LogoBar>
        <CarCards></CarCards>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import LogoBar from './views/LogoBar'
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
