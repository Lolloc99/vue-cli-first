<template>
  <div id="app">
    <JumbotronProva />
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <TitleProva />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import TitleProva from "./components/TitleProva.vue";
import JumbotronProva from "./components/JumbotronProva.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    TitleProva,
    JumbotronProva,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
