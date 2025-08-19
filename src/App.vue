<template>
  <img alt="Vue logo" src="https://transparencia.durango.gob.mx/_next/image?url=https%3A%2F%2Fs3.amazonaws.com%2Fnewtransp%2Flogos_organismos%2Futm_1678297396267.jpg&w=256&q=75">
  <br>
  <h1 class="proseso">EN PROCESO</h1>
  <br>
  <hello-world />
  <br>
  <pie-de-pag />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import PieDePag from './components/PieDePag.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    PieDePag,
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
.proceso {
  text-align: center;

}
</style>
