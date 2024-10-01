<template>
  <v-toolbar color="transparent">
    <v-container class="d-flex pa-0">
    <v-toolbar-title>
      <v-img src="../assets/logo.svg" class="logo" max-height="45" max-width="45"></v-img>
    </v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items>
      <v-button-navigation class="d-flex">
        <v-btn ><a href="#home"> Home </a></v-btn>
        <v-btn ><a href="#projetos"> Projetos </a></v-btn>
        <v-btn ><a href="#certificacoes"> Certificações </a></v-btn>
      </v-button-navigation>
    </v-toolbar-items>
    </v-container>
  </v-toolbar>
</template>

<script setup>
</script>

<style scoped>
  a {
    text-decoration: none;
    color: #c6d8d3;
  }
</style>