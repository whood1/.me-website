<template>
  <div>

    <Portfolio/>

    <img alt="Vue logo" src="./assets/logo.png">
    <div>
      <HelloWorld msg="Welcome to Your Vue.js App"/>
    </div>
  </div>

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Portfolio from './components/Portfolio.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Portfolio
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
