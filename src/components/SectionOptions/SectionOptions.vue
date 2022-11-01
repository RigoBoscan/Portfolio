<template>
  <v-container class="container-options text-center">
    <h2 class="title-options mt-4">¿Qué te interesa saber de mi?</h2>
    <v-row
      class="buttons-container"
      no-gutters
      align="center"
      justify="space-between"
    >
      <v-btn
        :to="{ name: 'about' }"
        height="93px"
        width="164px"
        class="btn-option"
        color="#ffffff"
      >
        <img width="24px" src="../../assets/icons/experience-icon.png" alt="" />
        <p class="mb-0 mt-2">Experiencia</p>
      </v-btn>
      <v-btn         :to="{ name: 'skills' }" height="93px" width="164px" class="btn-option" color="#ffffff">
        <img width="27px" src="../../assets/icons/skills-icon.png" alt="" />
        <p class="mb-0 mt-2">Habilidades</p>
      </v-btn>
      <v-btn height="93px" width="164px" class="btn-option" color="#ffffff">
        <img width="27px" src="../../assets/icons/studies-icon.png" alt="" />
        <p class="mb-0 mt-2">Estudios</p>
      </v-btn>
      <v-btn height="93px" width="164px" class="btn-option" color="#ffffff">
        <img width="29px" src="../../assets/icons/proyects-icon.png" alt="" />
        <p class="mb-0 mt-2">Proyectos</p>
      </v-btn>
      <v-btn height="93px" width="164px" class="btn-option" color="#ffffff">
        <img
          width="30px"
          src="../../assets/icons/personality-icon.png"
          alt=""
        />
        <p class="mb-0 mt-2">Personalidad</p>
      </v-btn>
      <v-btn height="93px" width="164px" class="btn-option" color="#ffffff">
        <img width="27px" src="../../assets/icons/hobbies-icon.png" alt="" />
        <p class="mb-0 mt-2">Hobbies</p>
      </v-btn>
    </v-row>
  </v-container>
</template>
<script>
export default {};
</script>

<style lang="scss">
@import "./SectionOptions.scss";
</style>
