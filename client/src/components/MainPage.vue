<template>
  <v-container class="pa-0">
    <section id="home" class="container-introducao d-flex flex-column text-center justify-center">
      <h3 class="text-h3 title-font variant-white">
        Olá, eu sou <span class="gradiant title-font">Vinicius Cintra</span>
      </h3>
      <p class="paragraph-font"> Desenvolvedor web front-end </p>
      <div class="mt-4">
        <v-btn color="#7371FC" class="ma-2">
            <a href="https://github.com/Vinicius-Cintra-Ferreira" target="_blank" class="d-flex align-center">
            <v-icon class="mr-2">
              mdi-github
            </v-icon> 
            <span>
              GitHub
            </span>
            </a>
        </v-btn>
        <v-btn color="#7371FC" class="ma-2">
            <a href="https://www.linkedin.com/in/vinicius-cf/" target="_blank" class="d-flex align-center">
            <v-icon class="mr-2">
              mdi-linkedin
            </v-icon> 
            <span>
              LinkedIn
            </span>
            </a>
        </v-btn>
      </div>
    </section>
    <section id="projetos" class="d-flex flex-column mt-4">
      <h3 class="py-4 text-h4 title-font variant-black detalhe">
        Projetos
      </h3>
      <div class="container-lista mb-10">
        <ul class="d-flex projetos-lista py-1">
          <v-card class="d-flex flex-column">
            <img src="../assets/projetos/bikcraft.png" alt="Bickcraft">
            <div class="info-projeto pa-4">
              <h3 class="">Bickcraft</h3>
              <span class="">Desenvolvido no curso HTML e CSS para Iniciantes - Origamid.</span>
            </div>
          </v-card>
          <v-card class="d-flex flex-column">
            <img src="../assets/projetos/techno.png" alt="Techno">
            <div class="info-projeto pa-4">
              <h3 class="">Techno</h3>
              <span class="">Desenvolvido com propósito acadêmico.</span>
            </div>
          </v-card>
          <v-card class="d-flex flex-column">
            <img src="../assets/projetos/lobo.png" alt="Lobo">
            <div class="info-projeto pa-4">
              <h3 class="">Lobo</h3>
              <span class="">Desenvolvido no curso: HTML e CSS para Iniciantes - Origamid</span>
            </div>
          </v-card>
        </ul>
      </div>
    </section>
  </v-container>
</template>

<script setup>  
</script>

<style scoped>
  .container-introducao {
    height: 540px;
  }

  a {
    text-decoration: none;
    color: #c6d8d3;
  }

  img {
    width: 100%;
    height: 100%;
    object-fit: contain;
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
  
  .paragraph-font {
    color: #c6d8d3;
    font: 200 1.5rem "Bliker", sans-serif;
    letter-spacing: 2px;
  }

  .variant-white {
    color: transparent;
    -webkit-text-stroke: 1.5px #c6d8d3;
  }

  .variant-black {
    color: transparent;
    -webkit-text-stroke: 1.5px #000;
  }

  .projetos-lista {
    list-style: none;
    gap: 20px;
    flex-wrap: nowrap;
    overflow-x: auto;
  }

  .projetos-lista > * {
    min-width: 550px;
    height: 330px;
  }

  .info-projeto {
    border-top: 2px solid #7371FC;
  }
</style>