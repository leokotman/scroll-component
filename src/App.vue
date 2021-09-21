<template>
  <div id="app">
    <the-scroller></the-scroller>
  </div>
</template>

<script>
import TheScroller from "./components/TheScroller.vue";

export default {
  name: "App",
  components: {
    TheScroller,
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
