<template>
  <div id="app">
  <mt-header fixed title="头部"></mt-header>
    <router-view></router-view>
    <mt-tabbar v-model="selected">
  <mt-tab-item id="外卖">
    <img slot="icon" >
    外卖
  </mt-tab-item>
  <mt-tab-item id="订单">
    <img slot="icon" >
    订单
  </mt-tab-item>
  <mt-tab-item id="发现">
    <img slot="icon" >
    发现
  </mt-tab-item>
  <mt-tab-item id="我的">
    <img slot="icon" >
    我的
  </mt-tab-item>
</mt-tabbar>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
