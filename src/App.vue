<template>
  <div id="app">
    <div id="board">
      <div id="panel-menu"><PanelMenu/></div>
      <div id="panel"><Panel/></div>
      <div id="panel-option"><PanelOption/></div>
    </div>
  </div>
</template>

<script>
import Panel from './components/Panel.vue'
import PanelMenu from './components/PanelMenu.vue'
import PanelOption from './components/PanelOption.vue'

export default {
  name: 'App',
  components: {
    Panel,
    PanelMenu,
    PanelOption
  }
}
</script>

<style>
body{
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: #34aeee;
  width: 100vw;
  height: 100vh;
  margin: 0;
  display: flex;
  align-items: center;
  justify-content: center;
}
#board {
  width: 80%;
  height: 500px;
  display: flex;
  color: white;
  overflow: hidden;
}
#panel{
  width:calc(100% - 240px);
  height: 100%;
  background-color: #34aeee;
  display: flex;
  align-items: center;
  justify-content: center;
}
#panel-menu{
  width: 70px;
  height: 100%;
  background-color: darkslategrey;
  border-radius: 7px;
}
#panel-option{
  width: 170px;
  height: 100%;
  background-color: darkslategrey;
  border-radius: 7px;
}
</style>
