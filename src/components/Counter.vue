<template>
  <h1>{{num}}</h1>
  <button @click="onClick()">Increment</button>
</template>

<script>
export default {
  name: 'Counter',
  data() {
    return{
      num: 0
    }
  },
  methods:{
    onClick(){
      this.num++
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
