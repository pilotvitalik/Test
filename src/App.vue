<template>
  <div id="app">
    <Wrapper/>
  </div>
</template>

<script>
import Wrapper from './components/Wrapper/Wrapper.vue'

export default {
  name: 'app',
  components: {
    Wrapper,
  },
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
*{
  margin: 0;
  padding: 0;
}
</style>
