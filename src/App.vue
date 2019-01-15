<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/donut.jpg">
    <HelloWorld msg="Donuts are delicious"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
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
  background-color: papayawhip;
  margin-top: 60px;
}
</style>
