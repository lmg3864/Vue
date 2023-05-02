<template>
  <div id="app">
    <MyHome></MyHome>
    <MyAbout></MyAbout>
  </div>
</template>

<script>
import MyHome from "./views/MyHome.vue"
import MyAbout from "./views/MyAbout.vue"

export default {
  name: 'App',
  components: {
    MyHome,
    MyAbout,
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
  margin-top: 60px;
}
</style>
