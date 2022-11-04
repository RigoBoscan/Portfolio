<template>
  <v-app-bar height="80px" app color="#F8FBFF" dark>
    <div class="d-flex align-center header">
      <h2>PORTFOLIO</h2>

      <v-img
        alt="Vuetify Name"
        class="shrink mt-1 hidden-sm-and-down"
        contain
        min-width="100"
        src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
        width="100"
      />
    </div>

    <v-spacer></v-spacer>

    <v-btn
      width="140px"
      height="47px"
      depressed
      color="#E5EFFF"
      class="btn-contact"

    >
      Contáctame
    </v-btn>
  </v-app-bar>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "./header.scss";
</style>
