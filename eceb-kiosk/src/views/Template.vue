<template>
  <v-container fluid class="template page">
    Template Here
    <v-btn to="/" x-large id="back-button">Back</v-btn>
  </v-container>
</template>

<script>

export default {
  name: 'Template'
}

</script>

<style scoped>

  #back-button {
    position: absolute;
    width: auto;
    bottom: 20px;
    right: 20px;
  }

</style>