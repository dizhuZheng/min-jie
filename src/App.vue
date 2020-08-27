<template>
  <div id="app">
    <div class="w3-top">
  <div class="w3-bar w3-blue w3-card">
    <a class="w3-bar-item w3-button w3-padding-large w3-hide-medium w3-hide-large w3-right" href="javascript:void(0)" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
    <span id="name" class="w3-bar-item w3-padding-large">重庆敏捷化工产品有限公司</span>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">网站首页</a>
    <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hide-small">产品分类</a>
    <div class="w3-dropdown-hover w3-hide-small">
      <button class="w3-padding-large w3-button" title="More">新闻中心<i class="fa fa-caret-down"></i></button>
      <div class="w3-dropdown-content w3-bar-block w3-card-4">
        <a href="#" class="w3-bar-item w3-button">最新公告</a>
        <a href="#" class="w3-bar-item w3-button">公司动态</a>
        <a href="#" class="w3-bar-item w3-button">行业新闻</a>
      </div>
    </div>
    <div class="w3-dropdown-hover w3-hide-small">
      <button class="w3-padding-large w3-button" title="More">关于我们<i class="fa fa-caret-down"></i></button>
      <div class="w3-dropdown-content w3-bar-block w3-card-4">
        <a href="#" class="w3-bar-item w3-button">企业简介</a>
        <a href="#" class="w3-bar-item w3-button">企业文化</a>
        <a href="#" class="w3-bar-item w3-button">企业荣誉</a>
        <a href="#" class="w3-bar-item w3-button">组织架构</a>
      </div>
    </div>
    <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hide-small">应用范围</a>
    <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hide-small">成功案例</a>
    <a href="javascript:void(0)" class="w3-padding-large w3-hover-red w3-hide-small w3-right"><i class="fa fa-search"></i></a>
  </div>
</div>

<!-- Navbar on small screens (remove the onclick attribute if you want the navbar to always show on top of the content when clicking on the links) -->
<div id="navDemo" class="w3-bar-block w3-black w3-hide w3-hide-large w3-hide-medium w3-top" style="margin-top:46px">
  <a href="#band" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">BAND</a>
  <a href="#tour" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">TOUR</a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">CONTACT</a>
  <a href="#" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">MERCH</a>
</div>
  <HelloWorld msg="创新无止境，品质树形象"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
}
body,h1,h2,h3,h4,h5,h6 {font-family: "Lato", sans-serif}
#name{
color: #fafafa;
letter-spacing: 0;
text-shadow: 0px 1px 0px #999, 0px 2px 0px #888, 0px 3px 0px #777, 0px 4px 0px #666, 0px 5px 0px #555, 0px 6px 0px #444, 0px 7px 0px #333, 0px 8px 7px #001135 }
.w3-bar,h1,button {font-family: "Montserrat", sans-serif}

.fa-search{font-size:20px;}
</style>
