<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld />
    <Galleria />
    <Galleria />
    <Galleria />
    <Galleria />
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Galleria from './components/Galleria.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Galleria
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
