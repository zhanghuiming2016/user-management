<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
  import Vue from 'vue';

  export default {
    name: 'App'
  }
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  background: #efefef;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  background: #efefef;
}
.ant-table-pagination.ant-pagination {
  float: left;
  position: relative!important;
  left: 50%!important;
  transform: translate(-50%)!important;
}
</style>
