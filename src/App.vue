<template>
  <div id="app">
    <!-- <img src="./assets/logo.png"> -->
    <Login/>
    <Vendor/>
  </div>
</template>

<script>
import Login from './components/Login'
import Vendor from './components/Vendor'

export default {
  name: 'App',
  components: {
    Login, Vendor
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
