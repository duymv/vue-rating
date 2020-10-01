<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <RatingController vue_rating="Vue Rating" username="Jonny" />
  </div>
</template>

<script>
import RatingController from "./components/RatingController.vue";

export default {
  name: "app",
  components: {
    RatingController
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
