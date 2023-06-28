<template>
  <div class="hello">
    <btn v-on:click="testClick()">Test</btn>
    <btn href="https://www.google.com/">  Test2</btn> 
    <btn>Test3</btn>

  </div>
</template>

<script>
import btn from  '/components/ourBtn.vue'
export default {
  name: 'HelloWorld',
  props: {
   
  },
  components: {
    btn
  },
  methods:{ 
    testClick:function(){ 
      alert("btn TEST clicked")
    }
  }
}
</script>