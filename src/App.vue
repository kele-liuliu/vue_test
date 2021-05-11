<template>
  <div id="app">
    <Box />
    <img alt="Vue logo" src="./assets/logo.png" />
    <Img />
  </div>
</template>

<script>
import Box from "./components/box.vue";
import Img from "./components/img.vue";

export default {
  name: "App",
  components: {
    Box,
    Img,
  },
};
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
