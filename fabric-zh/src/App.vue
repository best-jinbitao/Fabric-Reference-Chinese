<template>
  <div id="app">
    <div
      style="width:100%;height:39px;position:fixed;top:0;text-align:left;font-size:30px;padding:10px;border-bottom:1px solid #E4E7ED">
      Fabricjs中文文档
    </div>
    <el-container>
      <el-aside width="200px">
        <Menu style="position:fixed; height:100vh; overflow: auto;" />
      </el-aside>
      <el-main>
        <router-view></router-view>
      </el-main>
    </el-container>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Menu from './components/menu.vue'

export default {
  name: 'App',
  components: {
    Menu
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
