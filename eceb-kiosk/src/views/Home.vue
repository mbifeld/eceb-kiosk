<template>
  <div class="home">
    <div class="touch-instruction"> TOUCH TO BEGIN </div> 
    <div class="title"> The ECEB has saved over 500 Polar Bears to date! </div>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <div class="touch-instruction bottom"> TOUCH TO BEGIN </div> 
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">
.title {
  color: blue;
}

.touch-instructions {
  position: absolute;
  left: 44.01%;
  right: 43.96%;
  top: 5.28%;
  bottom: 92.87%;

  font-family: "Proxima Nova Bold" !important;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 20px;

  /* identical to box height */
  text-align: right;
  letter-spacing: 5px;

  color: #FFFFFF;
}

.bottom {
  top: 92.87% !important;
  bottom: 5.28% !important;
}

</style>

