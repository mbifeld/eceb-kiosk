<template>
  <v-container fluid class="home page">
    <v-container fluid id="home-title">
      Welcome To The ECEB
    </v-container>
    <v-container fluid id="home-buttons">
      <v-btn to="/about" x-large id="about-button">About</v-btn>
      <v-btn to="/template" x-large id="template-button">Template</v-btn>
    </v-container>
  </v-container>
</template>

<script>

export default {
  name: 'Home'
}
</script>

<style scoped>

  #home-title {
    position: absolute;
    width: 100%;
    top: 45%;
    text-align: center;
    font-size: 36px;
    padding: 0;
    margin: 0;
  }

  #home-buttons {
    position: absolute;
    width: auto;
    bottom: 20px;
    right: 1%;
  }

  #about-button {
    margin-right: 50px;
  }

</style>
