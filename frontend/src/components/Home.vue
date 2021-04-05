<template>
  <div class="home">
'    <NavBar/>
    <img class="home-img" src="../assets/img/coffee1.jpeg" alt="coffee img home page" />
    <div class="words">
      <p class="title">Sinta o sabor</p>
      <p class="sub-title">Sinta o poder de degustar café em sua casa</p>
    </div>
    <button class="home-btn"><a href="#">Junte-se</a></button>'
  </div>
</template>

<script>
import NavBar from "./NavBar"
export default {
  name: 'Home',
  components: {
    NavBar,
  }
}
</script>

<style>
*{
  margin:0;
  padding: 0;
  box-sizing: border-box;
}
.words{
  display:flex;
  justify-content: center;

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


</style>
