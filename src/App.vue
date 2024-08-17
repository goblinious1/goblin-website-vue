<template>
  <GlassContainer width="80%"><h1>securly.com.webcr.top</h1>
  now with 80% fewer colors</GlassContainer><br>
  <hr>
  <div class="content">
    <GlassContainer width="fit-content">
      <ClickableGlass expandable="true">hi</ClickableGlass>
    </GlassContainer>
    <GlassContainer block="false" width="350px" height="100%">
      <h1>FAQ</h1>
      <h3>Why "securly.com.webcr.top"?</h3>
      when securly checks a domain, it sends a request to securly.com, and to prevent it from checking that request causing an infinite loop, any domain with securly.com inside it will be unblockable!
      <h3>who are you</h3>
      im batman >:)
    </GlassContainer>
  </div>
</template>

<script>
import ClickableGlass from './components/ClickableGlass.vue';
import GlassContainer from './components/GlassContainer.vue'
export default {
  name: 'App',
  components: {
    GlassContainer,
    ClickableGlass
  }
}
</script>

<style>
.content {
  display: flex;
}
body {
  margin: 0px !important;
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
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #cfcfcf;
}
</style>
