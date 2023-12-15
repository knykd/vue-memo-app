<template>
  <nav>
    <router-link to="/">Home</router-link> | 
    <router-link to="New">New</router-link> | 
    <router-link to="/about">About</router-link>
    <HelloWorld></HelloWorld>
  </nav>
  <router-view/>
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
  color: #2c3e50;
  margin: 0 auto;
  max-width: 600px;
}

h1 {
  text-align: center;
}

nav {
  padding: 30px;
  text-align: center;
}
</style>
