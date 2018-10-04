
<template>
  <div id="app">
    <div class="nav">
          <span class="userIdentity">Administration</span>
    </div>

    <router-view/>
  </div>
</template>

<script>
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
}
/*
* 重置
*/
html, body{width:100%;height:100%;overflow-x:hidden;overflow-y:auto;-webkit-overflow-scrolling:touch;padding: 0;margin: 0}
body{background-color:#FBF9FE;}
::-webkit-scrollbar{width:0;height:0;}
::-webkit-inner-spin-button{-webkit-appearance:none;appearance:none;}
.nav{width:100%;height:100px;background-color:#fff;background-image:url(./assets/banner_ejbca-admin.png); background-repeat:no-repeat;
  background-position:left;margin:8px;}
.userIdentity{font-size:45px;margin-left:-550px;display: block;padding-top:20px;}
p{margin:0;padding:0}
li{list-style:none;}
a{color:#333;text-decoration: none}
a:active{color:#777;}

input{outline:none;}

#app{height: 100%;}
</style>
