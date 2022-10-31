<template>
  <v-app>
    <headerVue />
    <v-main>
      <router-view />
      <FooterVue />
    </v-main>
  </v-app>
</template>

<script>
import headerVue from "./components/layouts/header/header.vue";
import FooterVue from "./components/layouts/footer/Footer.vue";
export default {
  name: "App",

  data: () => ({
    //
  }),

  components: {
    headerVue,
    FooterVue,
  },
};
</script>
