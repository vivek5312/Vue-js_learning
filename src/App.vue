<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Vivek Vue.js App"/>
  <HomeView/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HomeView from './components/HomeView.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    HomeView
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
