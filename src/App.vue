<template>
  <div id="app">
    <myheader></myheader>
     <nav>
      <router-link to="/">Home</router-link> | 
      <router-link to="/about">About</router-link>  
    </nav>
    <main>
      <router-view />
    </main>
    <myfooter />
  </div>
</template>

<script>
import myfooter from './components/footer.vue'
import myheader from './components/header.vue'
export default {
  name: 'App',
  components: {
    myfooter,
    myheader
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align:center;
  color: #2c3e50;
  margin-top: 0px;
}
</style>
