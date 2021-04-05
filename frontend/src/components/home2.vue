<template>
    <div class="hometwo">
        <NavBar/>
        <div class="home2-phrases">
            <p>Descubra seu novo sabor de café</p>
            <p>Juntando-se a nós, você pode beneficiar o seu paladar degustando os últimos grãos do mercado</p>
        </div>
        <img class="coffe_bag1" src="../assets/img/coffee_bag1.png"/>
        <div class="cards-icon">
            <img class="card1" src="../assets/img/beans-card.png"/>
            <img class="card2" src="../assets/img/like-dislike-card.png"/>
        </div>
        <Footer/>
    </div>
</template>

<script>
import NavBar from "./NavBar"
import Footer from "./Footer"

export default {
    name:"Home2",
    components:{
        NavBar,
        Footer
    }
}
</script>
<style scoped>
    
</style>