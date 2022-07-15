<template>
  <div id="app">
    <Header />

    <MainContent />
    <MainBottom />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import MainContent from "./components/MainContent.vue";
import MainBottom from "./components/MainBottom.vue";

export default {
  name: "App",
  components: {
    Header,
    MainContent,
    MainBottom,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap.scss";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

main {
  background-color: black;
  color: white;
}
</style>
