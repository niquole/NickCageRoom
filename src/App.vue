<template>
  <div id="app">
    <nick/>
  </div>
</template>

<script>
import nick from './components/nick.vue'


export default {
  name: 'app',
  components: {
    nick
  },
  data() {
    return {
      x: "",
      y: ""

    }
  },
  methods: {
    move: function(event) {
      this.x = event.clientX;
      this.y = event.clientY;
    }
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
