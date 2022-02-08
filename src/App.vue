<template>
  <div id="app">
    <div class="component-style">
      
      <HomePage/>
    </div>
    
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue'


export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Noto+Sans&display=swap');
#app {
  font-family: 'Noto Sans', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: black;
}
</style>
