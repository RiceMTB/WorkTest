<template>
  <div :style="{'background':setcolor}" >
    {{canview}}
  </div>
</template>

<script>
export default { 
  props:['canview'],
  computed:{
    setcolor(){ 
      let myColor= ''
      if(this.canview=="Banana"){
        myColor= "yellow"
      }
      else if(this.canview=="apple"){ 
        myColor= "red"
      }
      return myColor
    }
  }
};
</script>


