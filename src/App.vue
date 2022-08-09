<template>
  <body>
    <product-hero></product-hero>
    <product-info></product-info>
    <page-footer></page-footer>
  </body>
</template>

<script>
import ProductHero from "@/components/productHero.vue";
import ProductInfo from "@/components/productInfo.vue";
import PageFooter from "@/components/pageFooter.vue";

export default {
  name: "App",
  components: {
    ProductHero,
    ProductInfo,
    PageFooter,
  },
};
</script>

<style>
</style>
