<template>
    <div @click="move">
        <img src="../assets/nick.png" alt="" :style="{top: y, left: x}">
    </div>
</template>

<script>
export default {
    name: 'nick',
  data() {
    return {
      x: null,
      y: null

    }
  },
  methods: {
    move: function(e) {
      this.x = `${e.clientX}px`;
      this.y = `${e.clientY}px`;

    //   this.x = event.clientX;
    //   this.y = event.clientY;
    }
  }
}
</script>

<style>
body {
    margin: 0;
}
div {
    height: 100vh;
    width: 100vw;
    background-image: url('http://s3-us-west-2.amazonaws.com/capitalradio-code/wp-content/uploads/2019/05/fire.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}

img {
    margin: 0;
    height: 100px;
    position: absolute;
}
</style>

