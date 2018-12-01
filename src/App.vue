<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <GridSample args="Possible arguments"/>
  </div>
</template>

<script>
import GridSample from './components/GridSample.vue'

export default {
  name: 'app',
  components: {
    GridSample
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
