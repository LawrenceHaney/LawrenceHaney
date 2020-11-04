<template>
  <div id="app">
    <navbar/>
    <main class="container-fluid">
    <HelloWorld/>
    <about/>
    <projects/>
    <history/>
    <links/>
    <flavor/>
    </main>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import navbar from "./components/nav-bar.vue"
import projects from "./components/projects.vue"
import about from "./components/about.vue"
import history from "./components/history.vue"
import flavor from "./components/flavor.vue"
import links from "./components/links.vue"
export default {
  name: 'App',
  components: {
    HelloWorld,
    navbar,
    projects,
    about,
    history,
    flavor,
    links
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
