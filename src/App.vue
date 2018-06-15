<template>
  <div id="app">
    <div class="logo">
        <img class="logo" src="./assets/logo.png">
    </div>
    <Hello/>    
  </div>
</template>

<script>
import Hello from "./components/HelloWorld";
export default {
  components: {
    Hello
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
  margin: 40px 0 20px;
}
.logo {
  width: 200px;
  margin: 0 auto;
  
}
</style>
