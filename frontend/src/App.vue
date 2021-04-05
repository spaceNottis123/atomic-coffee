<template>
  <HomePage/>
</template>

<script>
import HomePage from "../src/components/HomePage"
export default {
  name: 'App',
  components: {
    HomePage
  }
}
</script>

<style >
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  background:#594E36 ;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
