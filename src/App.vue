<template>
  <div id="app">
    <img src="./assets/logo.png">
    <hr>
    <button class="btn btn-primary">Confirm</button>
    <button class="btn btn-success">Success</button>
    <button class="btn btn-danger">Danger</button>
    <hr>
    <div class="myclass1">HelloWorld </div>
    <hr>
    <p>
           <!-- 使用 router-link 组件来导航. -->
           <!-- 通过传入 `to` 属性指定链接. -->
           <!-- <router-link> 默认会被渲染成一个 `<a>` 标签 -->
           <router-link to="/">Home</router-link>
           <router-link to="/news">新闻</router-link>
           <router-link to="/about">关于</router-link>
     </p>
    <router-view/>
  </div>
</template>

<script>
import './assets/my.css'
export default {
  name: 'App'
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
