<template>
  <v-app>
    <headerVue />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script>
import headerVue from "./components/layouts/header/header.vue";
export default {
  name: "App",

  data: () => ({
    //
  }),

  components: {
    headerVue,
  },
};
</script>
