<template>
  <div id="app">
      <img src="./assets/2.png" class="mingzi">
    <img src="./assets/3.png" class="youxiang">
    <img src="./assets/1.jpg" style="width:210px;height:110px;" class="logo">
   <img src="./assets/4.png" class="qianming">
    <signature></signature>
  
  </div>

</template>

<script>
import signature from './components/signature'

export default {
  name: 'app',
  components: {
    signature
  }
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
  position:relative;
}
.logo{
  position:absolute;
  left:250px;
  top:-370px;
}
.mingzi{
  position:absolute;
  top:-210px;
  left:10px;

}
.youxiang{
  position:absolute;
  top:-95px;
  left:10px;
}
.qianming{
  position:absolute;
 
  left:10px;
}
</style>
