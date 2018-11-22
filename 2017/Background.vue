<template>
  <div class="bg"></div>
</template>

<style lang="scss">
@import './colors.scss';

div.bg {
  width: 100vw;
  height: 100vh;
  z-index: -1000000;
  position: fixed;
  background-image: url('./background_blur.jpg');
  background-size: cover;
  filter: brightness(40%);
  background-size: cover;
}
</style>
