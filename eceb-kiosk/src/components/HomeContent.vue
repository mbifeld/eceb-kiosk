<template>
  <div class="hello">
    <router-link :to="{ name: 'About'}" >{{ msg }}</router-link>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
a {
  color: #42b983;
}

.template {
  height: 100%;
}

.hello {
  height: 100%;

}
</style>
