<template>
  <div id="app">
    <router-view></router-view>

  </div>
</template>

<script>
import FastClick from 'fastclick'
FastClick.attach(document.body);
export default {
  name: 'App',
  components: {

  }
}
</script>

<style>
@import "./assets/css/base.css";
@import "./assets/css/reset.css";
@import "./assets/css/iconfont.css";
</style>
