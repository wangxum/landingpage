<template>
  <div id="app">
    <nav-menu></nav-menu>
    <div class="header">
     <top-bar>
     </top-bar>
    </div>
  </div>
</template>

<script>
import topBar from "./components/topbar.vue";
import navMenu from "./components/mobile/nav-menu.vue";

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  components:{
    topBar,
    navMenu
  }
}
</script>

<style lang="scss">
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.header{
  padding-left: 16px;
  padding-right: 16px;
  border-bottom: 1px solid #e0e0e0;
}

@media (min-width: 767px){
  .header {
    padding-left: 30px;
    padding-right: 30px;
  }
}

body{
    font-family: 'Microsoft YaHei',arial,sans-serif;
    margin: 0;
    width: 100%;
    height: 100%;
}

ol, ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

a {
    color: #448aff;
    cursor: pointer;
    text-decoration: none;
    transition: color .2s ease-out;
}
</style>
