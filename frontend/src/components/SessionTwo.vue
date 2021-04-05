<template>
    <NavBar/>
    <img  class="coffee-bag" src="../assets/img/coffee_bag1.png" alt="coffee bag image">

    <h3 class="sec-title">Descubra seu novo sabor de café</h3>
    <p class="sec-text">Juntando-se a nós, você pode beneficiar o seu paladar degustando os últimos grãos do mercado</p>
    <img class="dislike-card" src="../assets/img/like-dislike-card.png" />
    <img class="beans-card" src="../assets/img/beans-card.png"/>
    <Footer/>
</template>

<script>
import NavBar from "./NavBar"
import Footer from "./Footer"
export default {
    name:'SessionTwo',
    components:{
        NavBar,
        Footer
    }
}
</script>

<style scoped>
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  background-color:#594E36 ;
}

.sec-title{
  color:whitesmoke;
  font-size: 59px;
  position:absolute;
  top:948px;
  left: 35%;
  transform: translate(-50%,-50%);
}
.sec-text{
  color:whitesmoke;
  font-size: 29px;
  position:absolute;
  top:1021px;
  left: 35%;
  transform: translate(-50%,-50%);
}
.dislike-card{
  position:absolute;
  top:1209px;
  left: 626px;
  transform: translate(-50%,-50%);
}
.beans-card{
  position:absolute;
  top:1209px;
  left: 226px;
  transform: translate(-50%,-50%);
}
</style>