<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Code Step By Step.js App"/> -->
  <HomeScreen />
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import HomeScreen from './components/home.vue'

export default {
  name: 'App',
  components: {
   // HelloWorld,
    HomeScreen,
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
