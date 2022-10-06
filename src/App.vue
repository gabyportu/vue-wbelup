<template>
  <div id="app">
  <h1> Hola mundo </h1>
    <img alt="Vue logo" src="https://i.pinimg.com/222x/d0/03/e3/d003e3401897ec3cda8712eddd016f64.jpg">
    <HelloWorld msg="Bienvenido al mundo de POO"/>
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
  color: #2c3e50;
  margin-top: 60px;
}img{
  
}
</style>
