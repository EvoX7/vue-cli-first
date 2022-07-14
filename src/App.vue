<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyTitle/>

    <!-- <img src="./assets/laptop-desk.png" alt="jumbotron"> -->
    <HeroOne/>
  </div>
</template>

<script>
import MyTitle from './components/MyTitle.vue'
import HeroOne from './components/HeroOne.vue'

export default {
  name: 'App',
  components: {
    MyTitle,
    HeroOne,
  }
}
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Edu+NSW+ACT+Foundation&display=swap');

body {
  background: #dee0e6;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

img {
  clip-path: polygon(50% 100%, 0 0, 100% 0);
}
</style>
