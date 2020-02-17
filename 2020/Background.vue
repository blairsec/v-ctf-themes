<template>
  <div class="bg"></div>
</template>

<style lang="scss">
@import './colors.scss';

body {
  background-color: black;
}

div.bg {
  width: 100vw;
  height: 100vh;
  z-index: -1000000;
  position: fixed;
  background: url(bg.jpg);
  opacity: 0.45;
  background-size: cover;
  background-position: center center;
  position: fixed;
  height: 100%;
  width: 100%;
}
</style>
