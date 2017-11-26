<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <p>{{ userid }}</p>
    <input type="text" v-model="userid">
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      userid: 'xxxx'
    }
  }
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
}
</style>
