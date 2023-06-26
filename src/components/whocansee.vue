<template>
  <div class="whosee" >
    {{canview}}
  </div>
</template>

<script>
export default { 
  props:['canview'],
  computed:{
    setcolor:function(){ 
      if(canview=="banana"){
        return "red"
      }
      else if('canview'=="apple"){ 
        return "#B22222"
      }
    }
  }
};
</script>

<style>
.whosee{
  background: green;
  text-align:center;
  
}
</style>
