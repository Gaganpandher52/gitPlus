<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/GitHub-Mark.png">
    <HelloWorld msg="Git-Plus"/>
    <GithubApi/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import GithubApi from './components/GithubApi.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    GithubApi
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
img{
  height: 200px;
  width: 200px;
}
</style>
