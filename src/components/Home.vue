<template>
  <div class="home">
    <NavBar/>
    <div id="home-phrases">
      <p>Sinta o sabor</p>
      <p>Sinta o poder de degustar café em sua casa</p>
    </div>
    <div class="home-btn">
      <button><a href="#">Junte-se</a></button>
    </div>
    <div class="home-img">
      <img alt="coffee img home page" src="../assets/img/coffee1.jpeg"/>
    </div>
    <Home2/>
  </div>
</template>

<script>
import NavBar from "./NavBar"
import Home2 from "./home2"
export default {
  name: 'Home',
  components: {
    NavBar,
    Home2
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>
