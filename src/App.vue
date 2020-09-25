<template>
  <div id="app">
    <PicDay/>
  </div>
</template>

<script>
import PicDay from './components/PicDay'
export default {
  name: 'app',
  components: {
    PicDay
  }
}

</script>

<style>
body{
  background-color: aliceblue;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  padding: 100px; 
  padding-top: 50px;
}
</style>