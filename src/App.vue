<template>
  <div id="app">
    <img src="./assets/logo.png">
    <h1>{{ msg }}</h1>
    <Hello></Hello>
  </div>
</template>

<script>
import Hello from './components/hello.vue'

export default {
  components:{
    Hello
  },
  data () {
    return {
      msg: 'Hello Vue 2.0!'
    }
  }
}
</script>

<style>
body {
  font-family: Helvetica, sans-serif;
}
</style>
