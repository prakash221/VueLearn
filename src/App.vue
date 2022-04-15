<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <!-- <HomePage data="Passing Data from App" msg="Pass 2 or more data from App.vue"/> -->
  <TestifElse/>
  <!-- Using Component Multiple time -->
  <!-- <HomePage data="Passing Data from App" msg="Pass 2 or more data from App.vue"/> -->
  <LoopLearn/>

</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import HomePage from './components/Home'
// import TestifElse from './components/ifelsewithBtn'
import LoopLearn from './components/ForLoop'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    // HomePage,
    // TestifElse
    LoopLearn
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
