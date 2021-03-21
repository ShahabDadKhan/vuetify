<template>
  <v-app class="grey lighten-4">
    <the-navbar></the-navbar>

    <v-main class="mx-4">
      <router-view></router-view>
    </v-main>
  </v-app>
</template>

<script>
import TheNavbar from "./components/TheNavbar.vue";
export default {
  components: { TheNavbar },
  name: "App",
  data: () => ({
    //
  }),
};
</script>
