<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <Greet name="Ishan" heroName="batman"/>
  <Greet name="woah" heroName="superman"/>
</template>

<script>

import Greet from './components/Greet.vue'

export default {
  name: 'App',
  components: {
    Greet
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
