<template>
  <div id="app">
    <Landing />
    <Description />
    <Reasons />
    <Learn />
    <Agenda />
    <Location />
    <Registration />
    <Footer />

  </div>
</template>

<script>
import Description from './components/Description.vue'
import Landing from './components/Landing.vue'
import Reasons from './components/Reasons.vue'
import Learn from './components/Learn.vue'
import Agenda from './components/Agenda.vue'
import Location from './components/Location.vue'
import Registration from './components/Registration.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Landing,
    Description,
    Reasons,
    Learn,
    Agenda,
    Location,
    Registration,
    Footer
  }
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;400&display=swap');

#app {
  font-family: 'Poppins', sans-serif;
  /* -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale; */
  text-align: center;
}
</style>
