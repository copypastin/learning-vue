<script>
import w from './w.vue'
export default {
  components: { w },

  data() {
    components: {
      w
    }

    return {
      titleClass: "title",
      titleClass2: "title2"
    }
  }
}
</script>

<template>
  <div1>
   <h1 :class="titleClass">Hello world</h1> 
  </div1>
    
  <w :class="titleClass2"/>
</template>

<style>
.title {
  color: rgb(59, 52, 168)
  
}
.title2 {
  color: aqua;
}
</style>