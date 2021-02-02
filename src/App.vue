<template>
  
  <div id="app">
    <img alt="Vue logo"  width="150" src="\img\logo.png">
    <slider/>
    <contador/>
    <productos/>
    <formulario/>
    <footerLan/> 
  </div>
  
</template>

<script>
import slider from './components/slider.vue'
import contador from './components/contador.vue'
import productos from './components/productos.vue'
import formulario from './components/formulario.vue'
import footerLan from './components/footerLan.vue'



export default {
  name: 'App',
  components: {
    slider,
    contador,
    productos,
    formulario,
    footerLan
     
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
