<template>
  <v-container id="home" class="h-350 d-flex flex-column">
    <v-row >
      <v-col class="pa-0 text-center" height="100">
        <h3 class="text-h3 title-font variant">
          Olá, eu sou <span class="gradiant title-font">Vinicius Cintra</span>
        </h3>
      </v-col>
    </v-row>
    <v-row>
      <v-col class="pa-0 text-center">
        <p class="text-h5 paragraph-font"> Desenvolvedor web front-end </p>
      </v-col>
    </v-row>
  </v-container>
</template>

<script setup>  
</script>

<style scoped>
  .h-350 {
    height: 350px;
    min-height: 350px;
    max-height: 350px;
  }





  /* Importação da font - Primal */
  @font-face {
    font-family: "Primal";
    src: url('../fonts/Primal.otf') format('opentype');
    font-weight: normal;
    font-style: normal;
    color: #c6d8d3;
  }

  .title-font {
    font-family: "Primal", sans-serif;
  }

  .gradiant {
    background: linear-gradient(90deg, #7371FC 10%, #88d4ab 90%);
    background-clip: text;
    -webkit-text-fill-color: transparent;
    transition: filter 0.300ms;
    -webkit-text-stroke: 0px;
  }
  
  .gradiant:hover {
    filter: drop-shadow(0 0 8px #7371FC);
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