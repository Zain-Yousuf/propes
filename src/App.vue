<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <chaild v-bind:users="users"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import chaild from './components/chaild.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    chaild
  },
  data(){
    return {users:[
      {name:"Huni"},
      {name:"zain"},
      {name:"sufyan"},
      {name:"numan"}
      ]}
  }
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
