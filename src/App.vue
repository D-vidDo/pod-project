<template>
  <div id="app">
    <Landing />
    <Description />
    <Reasons />

  </div>
</template>

<script>
import Description from './components/Description.vue'
import Landing from './components/Landing.vue'
import Reasons from './components/Reasons.vue'

export default {
  name: 'App',
  components: {
    Landing,
    Description,
    Reasons
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
