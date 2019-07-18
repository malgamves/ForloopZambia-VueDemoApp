<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <directives></directives>

  </div>
</template>

<script>
import Directives from './components/Directives.vue'

export default {
  name: 'app',
  components: {
    Directives
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
