<template>
<div id="app">
  <img class="vue" src="./assets/logo.png" alt="Vue.js PWA">
  <hello-scene></hello-scene>
</div>
</template>

<script>
import HelloScene from './components/HelloScene'

export default {
  name: 'app',
  components: {
    HelloScene
  }
}
</script>

<style>
body {
  margin: 0;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

.vue {
  max-height: 50px;
  width: auto;
  position: fixed;
  bottom: 20px;
  left: 20px;
  z-index: 1;
}
</style>
