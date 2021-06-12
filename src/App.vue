<template>
  <div id="app">
    <Navbar/>
    <Posts/>
  </div>
</template>

<script>
import Navbar from "./components/Navigation/Navbar.vue";
import Posts from "./components/Views/Posts.vue";

export default {
  name: 'App',
  components: {
    Navbar,
    Posts
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
