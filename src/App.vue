<template>
  <div id="app">
    <myheader></myheader>
    <img alt="Vue logo" src="https://us-east-1-02890046-view.menlosecurity.com/c/0/i/aHR0cHM6Ly93d3cuZGlzcGF0Y2guY29tL2djZG4vcHJlc3RvLzIwMjMvMDIvMjgvTkNPRC8wYmIxNjU3Ni1lNTI5LTQyYjAtOWZhZi01NTcxMGJiOWJjNmQtMjcyMjA5XzE1MzZfcmdiXzEuanBnP3dpZHRoPTk4MCZoZWlnaHQ9Njk2JmZpdD1jcm9wJmZvcm1hdD1wanBnJmF1dG89d2VicA~~">
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
