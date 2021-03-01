<template>
  <div id="app">
    <img alt="Degenerate Selfie" src="./assets/logo.png">
    <intro msg="Nathan Ho (nkh361)"/>
    <br>
    <homebody msg="Experience"/>
  </div>
</template>

<script>
import intro from './components/intro.vue'
import homebody from './components/homebody.vue'
export default {
  name: 'App',
  components: {
    intro,
    homebody
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