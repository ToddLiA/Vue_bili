<template>
  <div id="app">
    <h1>你好{{name}}</h1>
  </div>
  
</template>

<script>

export default {
  name: 'App',
  components: {
    
  },
  props:{
    name:{
      type:String,
      required:true,
      default:'老王'
    }
  }
}
</script>

<style>

</style>
