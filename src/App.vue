<template>
  <div id="app">
    <ChooseNation />
  </div>
</template>

<script>
import ChooseNation from './components/ChooseNation.vue'

export default {
  name: 'app',
  components: {
    ChooseNation
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
