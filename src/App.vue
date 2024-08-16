<template>
  <GlassContainer><h1>securly.com.webcr.top</h1></GlassContainer>
  <GlassContainer><img alt="Vue logo" src="./assets/logo.png"><img alt="Vue logo" src="./assets/logo.png"></GlassContainer>
</template>

<script>
import GlassContainer from './components/Box.vue'

export default {
  name: 'App',
  components: {
    GlassContainer
  }
}
</script>

<style>
body {
  image-rendering: optimizeSpeed;             /* STOP SMOOTHING, GIVE ME SPEED  */
    image-rendering: -moz-crisp-edges;          /* Firefox                        */
    image-rendering: -o-crisp-edges;            /* Opera                          */
    image-rendering: -webkit-optimize-contrast; /* Chrome (and eventually Safari) */
    image-rendering: pixelated;                 /* Universal support since 2021   */
    image-rendering: optimize-contrast;         /* CSS3 Proposed                  */
    -ms-interpolation-mode: nearest-neighbor;   /* IE8+                           */

  background-image: url('https://i.pinimg.com/originals/b2/2a/a2/b22aa22b2f3f55b6468361158d52e2e7.gif');
  background-size: cover;
  height: 100vh;
  padding:0;
  margin:0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
