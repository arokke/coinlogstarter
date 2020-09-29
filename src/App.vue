<template>
<div class="container">
   <img alt="Vue logo" src="./assets/coinlog.png" class="hugeicon">
  <br>
  <HelloWorld msg="Coinlog"/>
</div>



 
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #D8DEE9;
  margin-top: 60px;
}
.progress-bar {
    background-color: #4C566A !important;
}
.hugeicon{
  width: 100px;
  height: 100px;
}
</style>
