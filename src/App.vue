<template>
  <div id="app">
    <img style="margin-left:280px" src="./assets/logo.png">
        <md-button style="margin-left:280px" class="md-icon-button nav-trigger" @click="toggleSidenav">

        <md-icon style="margin-left:280px" class="md-size-4x md-warn" md-src="./assets/logo.png"></md-icon>
        <md-icon>menu</md-icon>
      </md-button>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
/*body {
  margin: 0;
  padding: 0;
  background: #1f2d3d;
  font-family: Helvetica Neue,Helvetica,PingFang SC,Hiragino Sans GB,Microsoft YaHei,SimSun,sans-serif;
  font-weight: 400;
  -webkit-font-smoothing: antialiased;
}
#app {
  position: absolute;
  top: 0;
  bottom: 0;
  width: 100%;
}*/
</style>
