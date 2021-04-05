<template>
  <!--    <img src="../assets/img/SHOP-ICON.svg"/>-->
  <div class="navbar">
      <header>
        <img class="logo" src="../assets/img/logo.svg" alt="logo"/>
        <nav>
            <ul class="nav__links">
              <li><a href="#">Descubra</a></li>
              <li><a href="#">Loja</a></li>
              <li><a href="#">Junte-se</a></li>
              <li><a href="#"></a><img class="shop-icon" src="../assets/img/SHOP-ICON.svg"/></li>
            </ul>
        </nav>
      </header>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{
    box-sizing: border-box;
    padding: 0;
    margin: 0;
    background-color: #ffffff;
}
li,a{
  font-family: 'Courier New', Courier, monospace;
  font-weight: 500;
  font-size: 16px;
  color: black;
  text-decoration: none;
}
header{
  display:flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 10%;

}
.logo{
  cursor:pointer;
  margin-right: auto;
}
nav{
  order:1;
}
.nav__links{
  list-style: none;
  display: flex;
  align-items: center;
}
.nav__links li{
  display: inline-block;
  padding:0px 20px;
}
.nav__links li:nth-child(1){
  padding:0 20px 0 0;
}
.nav__links li a{
  transition: all 0.3s ease 0s;
}
.nav__links li a:hover {
  transition: all 0.3s ease 0s;
  color: #D0DDD7;
}
.shop-icon{
  width: auto;
  height: auto;
  padding: 10px;
  cursor: pointer;
}
.shop-icon:hover{
  transition: all 0.3s ease 0s;
  background: #D0DDD7;
  border-radius: 8px;
}


</style>
