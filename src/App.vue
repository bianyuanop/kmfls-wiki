<template>
<router-view/>
</template>

<script>
export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
html, body {
  height: 100%;
  overflow: hidden;
}
#app {
  height: 100%;
  width: 100%;

  display: flex;
  justify-content: center;
  align-items: center;

}
@font-face {
  font-family: 'Chalk';
  src: url('~@/assets/fonts/KGBlankSpaceSketch.ttf');
}
</style>
