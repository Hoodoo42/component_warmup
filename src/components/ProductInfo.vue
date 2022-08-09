<template>
    <div id="info">
<h4>The water we ship to you comes from crystal clear glacial waters of the north! Of course non of that matters becasue after a few good uses of our puddle package, you wont even beable to see through it anymore!"</h4>
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