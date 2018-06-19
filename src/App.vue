<template>
  <div id="app">
    <login></login>
    <activity></activity>
  </div>
</template>
<script>
import Login from "./components/login.vue";
// import Activity from "./components/activity.vue";
export default {
  name: "app",
  components: {
    Login,
    // Activity
  }
};
</script>

<style>
body {
  margin: 0;
}
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
