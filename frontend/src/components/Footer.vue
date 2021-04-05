<template>
    <ul id="footer">
        <li class="sobre"><a href="#">Sobre nos</a></li>
        <li class="contato"><a href="#">Contato</a></li>
        <li class="twitter"><a href="#">Twitter</a></li>
        <li class="facebook"><a href="#">Facebook</a></li>
    </ul>
</template>
<script>

export default {
    name:"Footer"    
}
</script>
<style scoped>
*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}
a{
    all: unset;
}
ul,li{
    display: flex;
    list-style: none;
    justify-content: space-between;
    align-items: center;
    background:#2F2504;
    padding: 15px 10%;
}
#footer {
    position: absolute;
    bottom:0;
    width: 100%;
}

.sobre,.contato,.twitter,.facebook{
    color:whitesmoke;
    margin:0.1rem;
    cursor:pointer;
}
</style>