<template>
  <div id="app">
    <Header/>
    <Jumbotron/>
    <Boolean/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Jumbotron from './components/Jumbotron.vue'
import Boolean from './components/Boolean.vue'

export default {
  name: 'App',
  components: {
    Header,
    Jumbotron,
    Boolean,
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
