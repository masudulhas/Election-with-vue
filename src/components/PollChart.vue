<template>
  <h1>Hello masud. Your age is {{age}}</h1>
</template>

<script>
  export default {
    props: {
      age: {
        type: Number,
        required: true
      } 
    }
  }
</script>

<style>

</style>
