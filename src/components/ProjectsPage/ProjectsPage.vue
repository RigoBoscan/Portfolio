<template>
  <v-container class="projects-container">
    <h1 class="mb-7">Proyectos</h1>
    <div class="container-projects__info" no-gutters>
      <div class="container-date__projects">
        <img class="image-project" src="../../assets/img/notario-img.png" alt="" />
        <p class="mt-5">NotarioExpress</p>
        <p class="parrafo-normal">
          La plataforma digital de trámites <br />
          notariales lider en Chile
        </p>
      </div>
      <div class="container-date__projects mt-15">
        <img class="image-project" src="../../assets/img/nuhome-img.png" alt="" />
        <p class="mt-5">NuHome</p>
        <p class="parrafo-normal">
          Te ayudamos a cumplir tu sueño de <br />
          tener casa propia
        </p>
      </div>
      <div class="container-date__projects mt-15">
       <div class="image-zoom">
        <img class="image-project" src="../../assets/img/alerth-img.png" alt="" />
       </div>
        <p class="mt-5">Alerth</p>
        <p class="parrafo-normal">
          Plataforma que brinda asistencia y <br />
          seguridad donde quiera que estes
        </p>
      </div>
    </div>
  </v-container>
</template>

<script>
export default {};
</script>

<style lang="scss">
@import "./ProjectsPage.scss";
</style>
