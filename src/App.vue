<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <A />
    <Nav />
  </div>
</template>

<script>
import A from "./components/a.vue";
import Nav from "./components/nav.vue";
export default {
  name: "App",
  components: { A, Nav },
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
