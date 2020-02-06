<template>
  <div id="app">
    <EnvironmentVariable />
  </div>
</template>

<script>
import EnvironmentVariable from './components/EnvironmentVariable.vue'

export default {
  name: 'app',
  components: {
    EnvironmentVariable
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
