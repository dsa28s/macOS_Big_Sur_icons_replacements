<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
import Home from './components/Home.vue'
import '@adobe/coral-spectrum/dist/js/coral.js'
import '@adobe/coral-spectrum/dist/css/coral.css'

// import parse from 'parse'
// parse.initialize("macOSicons");
// parse.serverURL = 'http://localhost:1337/parse'
// console.log(parse);

export default {
  name: 'App',
  components: {
    Home
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