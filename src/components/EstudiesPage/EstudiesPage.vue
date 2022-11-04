<template>
  <v-container class="container-estudies">
    <h1>Estudios</h1>
    <p class="parrafo-normal__grey mt-3 mb-0">
      Gran parte de mis conocimientos vienen de ser autodidacta, realizando
      cursos en diferentes plataformas de aprendizaje como Platzi, Udemy,
      Domestika y LinkedIn
    </p>
    <div v-for="(item, i) in estudies" :key="i">
      <p class="parrafo-normal__blue mt-10 mb-3">{{ item.title }}</p>
      <v-row no-gutters class="container-info__estudies">
        <v-flex class="information">
          <li>
            <img
              class="mr-1"
              width="16px"
              src="../../assets/icons/plataform-icon.png"
              alt=""
            />Plataforma
          </li>
          <li>
            <img
              class="mr-1"
              width="15px"
              src="../../assets/icons/state-icon.png"
              alt=""
            />Estado
          </li>
          <li>
            <img
              class="mr-1"
              width="15.5px"
              src="../../assets/icons/corazon-icon.png"
              alt=""
            />Satisfacción
          </li>
        </v-flex>

        <v-flex class="information text-right">
          <div>
            <li class="li-bold">{{ item.plataform }}</li>
            <li class="li-bold">{{ item.state }}</li>
            <li>
              <img width="89.85px" :src="item.img" alt="" />
            </li>
          </div>
        </v-flex>
      </v-row>
    </div>
  </v-container>
</template>

<script>
import { estudies } from "@/datadummy/Estudies";
export default {
  data() {
    return {
      estudies,
    };
  },
};
</script>

<style lang="scss">
@import "./EstudiesPage.scss";
</style>
