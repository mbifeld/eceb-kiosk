<template>
  <v-container fluid class="about-page">
    <v-container fluid id="about-title">
      About Slide
    </v-container>
    <v-container fluid id="about-buttons">
      <v-btn to="/" x-large id="back-button">Back</v-btn>
    </v-container>
  </v-container>
</template>

<script>

export default {
  name: 'Home'
}
</script>

<style scoped>

  .about-page {
    background: #13294B;
    height: 100%;
  }

  #about-title {
    position: absolute;
  }

  #about-buttons {
    position: absolute;
    width: auto;
    bottom: 5px;
    right: 10px;
  }

  #back-button {
    margin-right: 15px;
  }

</style>
