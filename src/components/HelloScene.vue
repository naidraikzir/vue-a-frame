<template>
<a-scene>
  <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
  <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
  <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
  <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#43C877"></a-plane>
  <a-sky color="#8ddfff"></a-sky>
</a-scene>
</template>

<script>
import 'aframe'

export default {
  name: 'HelloScene'
}
</script>

<style>
.fullscreen {
  height: 100vh;
  position: relative;
}
</style>
