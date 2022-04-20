<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <HelloGit/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloGit from './components/HelloGit.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    HelloGit
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
