<template>
    <div>
<main>
    <p>facebook is a social network website started by mark zuckerberg</p>
    <product-gallery></product-gallery>
</main>
    </div>
</template>

<script>
import ProductGallery from "@/components/productGallery.vue";
    export default {
        components:{
            ProductGallery
        }
    }
</script>

<style scoped>
main{
    color: blue;
    text-align: center;
}
</style>