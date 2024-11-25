<template>
  <v-app>
    <v-app-bar color="transparent" elevation="0">
      <HeaderBar />
    </v-app-bar>
    <v-main class="background">
    <MainPage />
    </v-main>
  </v-app>
</template>

<script setup>
</script>

<style scoped>
  .background {
    background-color: #0a0a0a80;
    box-shadow: inset 0 -460px #fdfdfd;
  }
</style>
