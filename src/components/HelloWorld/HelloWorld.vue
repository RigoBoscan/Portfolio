<template>
  <v-container class="container-animation">
    <div class="container-information pa-0">
      <h1>¡Hola!</h1>
      <h1 class="mt-9">
        Mi nombre <br />
        es Victor y soy un <br />
        <b class="b-blue">Diseñador UI</b>
      </h1>
      <img
        class="image-avatar mt-3"
        src="../../assets/img/victor-avatar.png"
        alt=""
      />
    </div>
    <div class="burbuja"></div>
    <div class="burbuja"></div>
    <div class="burbuja"></div>
    <div class="burbuja"></div>
    <div class="burbuja"></div>
    <div class="burbuja"></div>
    <div class="burbuja"></div>
    <div class="burbuja"></div>
    <div class="burbuja"></div>
    <div class="burbuja"></div>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({}),
};
</script>

<style lang="scss">
@import "./HelloWorld.scss";
</style>
