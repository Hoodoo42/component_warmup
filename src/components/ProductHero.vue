<template>
    <div id="main_ad">
        <h1>Get Your Very Own Puddle!</h1>
    
<img src="https://images.unsplash.com/photo-1588250715769-d1664ef3e081?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8N3x8cHVkZGxlfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=800&q=60" alt="a puddle on cobblestone">
    <h3>For a limited time only!</h3>
    <h4>While supplies last!</h4>
    </div>
</template>

<script>
    export default {
        name: 'product-hero'
    }
</script>

<style scoped>
#main_ad{
    display: grid;
    place-items: center;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    
    background-color: blanchedalmond;
}

img{
    height: 200px;
    width: 200px;
    border-radius: 80px;
    margin: 10px;
}
</style>