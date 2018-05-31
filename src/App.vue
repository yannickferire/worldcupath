<template>
  <div id="app">
    <ChooseNation />
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
  </div>
</template>

<script>
/*import HelloWorld from './components/HelloWorld.vue'*/
import ChooseNation from './components/ChooseNation.vue'

export default {
  name: 'app',
  components: {
    /*HelloWorld*/
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
