<!--
 * @Author: your name
 * @Date: 2020-07-27 11:55:51
 * @LastEditTime: 2020-07-27 11:56:01
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \test\test\src\App.vue
--> 
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
<<<<<<< HEAD
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Index/>
=======
    <HelloWorld msg="我创建了feature分支"/>
>>>>>>> feature_shunhua_xx
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Index from './components/Index.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Index
  }
}
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
