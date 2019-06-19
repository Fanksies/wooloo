<template>
  <div id="app">
    <Sheep />
    <h1>Beep Beep I'm a Sheep</h1>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Sheep from './components/sheep'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Sheep
  }
}
</script>

<style>
body, html {
  height:100%;
  margin:0;
  padding:0;
  background:#eee;
  display:flex; 
  flex-direction: column;
}

#app {
  flex:1;
  display:flex;
  flex-direction: column;
  justify-content: center;
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

svg {
  margin: 0 auto;
}

h1 {
  margin:0;
}
</style>
