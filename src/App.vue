<template>
  <div id="app">
    <MyChart/>
  </div>
</template>

<script>
import MyChart from './components/MyChart'


export default {
  name: 'App',
  components: {
    MyChart
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
