<template>
  <div id="app">
    <img alt="Vue logo" style="height: 40px" src="./assets/logo.png" />
    <br />
    <router-link to="/">子应用1：首页</router-link>
    <br />
    <router-link to="/hello">子应用1: hello 页</router-link>
    <br />
    <router-link to="/world">子应用1：world 页</router-link>
    <br />
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
