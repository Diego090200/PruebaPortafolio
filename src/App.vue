<template>
  <NavBar></NavBar>
  <InicioPresentacion></InicioPresentacion>
  <EduHabilidad></EduHabilidad>
  <contacto-redes></contacto-redes>
</template>

<script>
import ContactoRedes from './components/Contacto-Redes.vue';
import EduHabilidad from './components/Edu-Habilidad.vue';
import InicioPresentacion from './components/InicioPresentacion.vue';
import NavBar from './components/NavBar.vue';

export default {
  name: 'App',
  components: {
    NavBar,
    EduHabilidad,
    InicioPresentacion,
    ContactoRedes,
}
}
</script>,

<style>
  #app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #111827;
  min-height: 100vh;
}
body{
  margin: 0; 
  padding: 0;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  background-color: #111827;
  min-height: 100vh;
}
</style>
