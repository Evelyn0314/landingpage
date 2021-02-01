<template>
  
  <div id="app">
    <img alt="Vue logo" src="\img\logo.png">
    <slider/>
    <formulario/>
  </div>
  
</template>

<script>
import slider from './components/slider.vue'
import formulario from './components/formulario.vue'


export default {
  name: 'App',
  components: {
    slider,
    formulario, 
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
