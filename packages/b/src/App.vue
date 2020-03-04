<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    Here I am in Package B

    <Hello msg="Lerna" />
  </div>
</template>

<script>
import { Hello } from "a";

export default {
  name: "App",
  components: {
    Hello
  }
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
