<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view></router-view>
    <firstcomponent></firstcomponent>
  </div>
</template>

<script>
import firstcomponent from './components/firstcomponents.vue'

export default {
  name: 'app',
   data () {
    return {
      msg: 'Hello Vue!'
    }
  },
  components: { firstcomponent }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  display: flex;
}
</style>
