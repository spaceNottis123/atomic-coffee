<template>
  <div class="navbar">
      <nav>
          <ul>
            <li><a href="#"><img src="../assets/img/logo.png"/></a></li>
            <li><a href="#">Descubra</a></li>
            <li><a href="#">Loja</a></li>
            <li><a href="#">Junte-se</a></li>
            <li><a href="#"><img src="../assets/img/SHOP-ICON.png"/></a></li>
          </ul>
      </nav>
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
    padding: 0;
    margin: 0;
}
</style>
