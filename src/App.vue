<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="scss">
  @import "~@/assets/style/reset.scss";
  @import "~@/assets/style/helper.scss";
  body {
    line-height: 1.5;
    font-family: $font-hei;
    font-size: 16px;
    color: #333;
  }
  #app {
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
  }
</style>
