<template>
    <div @click="move">
        <img src="../assets/nick.png" alt="">
    </div>
</template>

<script>
export default {
    name: 'nick'

}
</script>

<style>
body {
    margin: 0;
}
div {
    height: 100vh;
    background-image: url('http://s3-us-west-2.amazonaws.com/capitalradio-code/wp-content/uploads/2019/05/fire.jpg');
    background-repeat: no-repeat;
    background-size: cover;
}

div img {
    position: absolute;
}
</style>

