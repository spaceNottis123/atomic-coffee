<template>
    <NavBar/>
    <img class="home-img" src="../assets/img/coffee1.jpeg" alt="coffee img home page" />
    <div class="words">
        <p class="title">Sinta o sabor</p>
        <p class="sub-title">Sinta o poder de degustar café em sua casa</p>
    </div>
    <button class="home-btn"><a href="#">Junte-se</a></button>
</template>

<script>
import NavBar from './NavBar.vue'

export default {
  name: 'HomePage',
  components: {
    NavBar
  }
}
</script>

<style >
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  background-color:#594E36 ;
}
a{
  all:unset;
}
.words{
  position:absolute;
  top:45%;
  left: 75%;
  transform: translate(-50%,-50%);
}
.home-btn{
  position:absolute;
  top:60%;
  left: 65%;
  transform: translate(-50%,-50%);
  cursor:pointer;
  width: 100px;
  height: 60px;
  border-radius: 78px;
  border-color: #A5AE9E;;
  background: #A5AE9E;
}
.title{
  font-size: 72px;
  color:whitesmoke;
}
.sub-title{
  font-size: 22px;
  color:whitesmoke;
}
.home-img{
  position:absolute;
  left:94px;
  top:230px;
  height: 407px;
  width: 527px;
}
.coffee-bag{
  position: absolute;
  top:1100px;
  left:80%;
  transform: translate(-50%,-50%);
}

</style>
