<template>
  <v-toolbar color="#211D26">
    <v-img src="../assets/logo.svg" class="logo ml-10" max-height="45" max-width="45"></v-img>
    <v-spacer></v-spacer>
    <nav>

    </nav>
  </v-toolbar>
</template>

<script setup>  
</script>

<style scoped>
  .logo{
    transition: filter 0.300ms;
  }
  .logo:hover {
    filter: drop-shadow(0 0 16px #7371FC);
  }
  nav ul {
    list-style: none;
  }
</style>