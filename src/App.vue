<template>
  <div id="app">
    <!-- <img src="./assets/proBG.png">
    <img src="./assets/logo.png"> -->
    <!-- <img src="assets/img/proBG.png">
    <img src="/static/img/logo.png"> -->
    <router-view @stateChanged="handleC"/>
  </div>
</template>

<script>
export default {
  name: 'App',
  methods: {
    handleC(arr) {
      console.log(arr);
    },
  },
};
</script>

<style>
#app {
  /* font-family: "Avenir", Helvetica, Arial, sans-serif; */
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  margin-top: 60px;
}
</style>
