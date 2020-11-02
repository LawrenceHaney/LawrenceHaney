<template>
  <div id="app container-fluid">
    <navbar/>
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import navbar from "./components/nav-bar.vue"

export default {
  name: 'App',
  components: {
    HelloWorld,
    navbar
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
