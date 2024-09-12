<template>
  <v-app>
    <HeaderBar />
    <v-container class="fill-height ">
      <v-row class="">
        <v-col cols="12" class="pa-0 text-center">
          <h3 class="text-h3 title-font variant">
            Olá, eu sou <span class="gradiant title-font">Vinicius Cintra</span>
          </h3>
          <p class="text-h5 paragraph-font">
            Desenvolvedor web front-end
          </p>
          
        </v-col>
      </v-row>
    </v-container>
  </v-app>
</template>

<script setup>  
</script>

<style scoped>
  /* Importação da font - Primal */
  @font-face {
    font-family: "Primal";
    src: url('../fonts/Primal.otf') format('opentype');
    font-weight: normal;
    font-style: normal;
    color: #c6d8d3;
  }

  .gradiant {
    background: linear-gradient(90deg, #7371FC 10%, #88d4ab 90%);
    background-clip: text;
    -webkit-text-fill-color: transparent;
    transition: filter 0.300ms;
    -webkit-text-stroke: 0px;
  }
  
  .gradiant:hover {
    filter: drop-shadow(0 0 16px #7371FC);
  }

  .title-font {
    font-family: "Primal", sans-serif;
  }
  
  .paragraph-font {
    font-family: "Fira Sans", sans-serif;
    color: #c6d8d3;
    font-weight: 300;
  }

  .variant {
    color: transparent;
    -webkit-text-stroke: 1.5px #c6d8d3;
  }
</style>