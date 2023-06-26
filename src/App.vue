<template>
  <div id="app">
    <myheader></myheader>
    <img alt="Vue logo" src="https://us-west-1-02890046-view.menlosecurity.com/c/0/i/aHR0cHM6Ly9pbWFnZXMucGV4ZWxzLmNvbS9waG90b3MvMjY4NTMzL3BleGVscy1waG90by0yNjg1MzMuanBlZz9jcz1zcmdiJmRsPXBleGVscy1waXhhYmF5LTI2ODUzMy5qcGcmZm09anBn">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
     <myfooter></myfooter>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import myfooter from './components/footer.vue'
import myheader from './components/header.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
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
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
