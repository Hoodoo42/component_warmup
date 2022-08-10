<template>
    <div id="info">
<h4>The water we ship to you comes from crystal clear glacial waters of the north! Of course non of that matters because after a few good uses of our puddle package, you wont even beable to see through it anymore!</h4>
    <h3>Now you can puddle jump, anywhere, anytime no need for rain!</h3>
    <ul>Included:</ul>
    <li>shipped in our patented triple reinforced resuable organic plastic packaging</li>
    <li>water pump to help get your puddle back into its carry case</li>
    <li>upgrade your package and recieve specially formulated puddle jumping boots that will be the envy of your friends and enemies!</li>
    <product-gallery></product-gallery>
    </div>
</template>

<script>
import ProductGallery from '@/components/ProductGallery.vue'
    export default {
        name: 'product-info',
        components:{
            ProductGallery
        }
        
    }
</script>

<style scoped>
#info{
    width: 50%;
    place-self: center;
    text-align: center;
    
}
</style>