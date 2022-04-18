<template>
<div>
  <div id='sidebar'>
  <Sidebar msg="Welcome to Your Vue.js App"/>
  </div>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    
    
  </div>
</div>
  

</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Sidebar from './components/SideBar.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Sidebar,
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
