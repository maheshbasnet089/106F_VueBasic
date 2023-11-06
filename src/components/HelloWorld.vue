<!-- <script setup>


defineProps({
  msg: String,
})


</script> -->




<template>

<div>
  <RenderHelloWorld />
</div>
 
</template>
<script>
import {h} from 'vue'
export default{

  components : {
    RenderHelloWorld : {
      render(){
        return h('h1','Hello i am Manish')
      }
    }
  }
}

</script>
<style scoped>
.read-the-docs {
  color: #888;
}
</style>
