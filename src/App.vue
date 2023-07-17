<template>
  <div id="app">
    <calculator msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import calculator from './components/Calculator.vue'

export default {
  name: 'App',
  components: {
    calculator
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
