<template>
  <v-container class="container-contact text-center">
    <h2>¿Te gustó mi perfil?</h2>
    <p>Contáctame y platiquemos</p>
    <img src="../../../assets/icons/hand.svg" alt="">
    <v-row
      align="center"
      justify="space-between"
      class="buttons-container mt-5"
      no-gutters
    >
      <v-btn class="button-contact" height="55px" width="100px" color="#FFFFFF"
        ><img height="19px" src="../../../assets/icons/mail-contact.png" alt=""
      /></v-btn>
      <v-btn class="button-contact" height="55px" width="100px" color="#61EE91"
        ><img
          height="25px"
          src="../../../assets/icons/whattsap-contact.png"
          alt=""
      /></v-btn>
      <v-btn class="button-contact" height="55px" width="100px" color="#0A66C2"
        ><img
          height="25px"
          src="../../../assets/icons/linkedin-contact.png"
          alt=""
      /></v-btn>
    </v-row>
  </v-container>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "./Footer.scss";
</style>
