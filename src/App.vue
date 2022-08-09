<template>
  <div id="app">
<product-hero></product-hero>
<product-info></product-info>
<page-footer></page-footer>
  </div>
</template>

<script>
import ProductHero from '@/components/ProductHero.vue'
import ProductInfo from '@/components/ProductInfo.vue'
import PageFooter from '@/components/PageFooter.vue'

export default {
  components:{
    ProductHero,
    ProductInfo,
    PageFooter
  }
}
</script>

<style>
#app{
  display: grid;
}
</style>
