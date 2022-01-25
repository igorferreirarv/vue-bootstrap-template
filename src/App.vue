<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/bootstrap.png" />
    <StartComponents />
  </div>
</template>

<script>
import StartComponents from "./components/Bootstrap.vue";

export default {
  name: "App",
  components: {
    StartComponents,
  },
};
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
