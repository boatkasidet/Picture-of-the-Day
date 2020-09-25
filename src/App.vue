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
  background: url("https://images8.alphacoders.com/105/thumb-1920-1057020.jpg");
  background-size: 100%;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  padding: 100px; 
  padding-top: 50px;
  color: white;
}
</style>