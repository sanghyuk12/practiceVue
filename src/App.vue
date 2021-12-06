<template>
  <div id="app">
<!--    <HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <Kedemo_pc_web msg="1313"/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
// import kedemo_pc_web from "@/components/kedemo_pc_web";
import Kedemo_pc_web from './components/Kedemo_pc_web'

export default {
  name: 'App',
  components: {
    Kedemo_pc_web
  }
}
</script>

<style scoped src="./assets/css/style.css">
#app {
  /*font-family: Avenir, Helvetica, Arial, sans-serif;*/
  /*-webkit-font-smoothing: antialiased;*/
  /*-moz-osx-font-smoothing: grayscale;*/
  /*text-align: center;*/
  /*color: #2c3e50;*/
  /*margin-top: 60px;*/
}
</style>
