<template>
    <div>
      <ProductImg/>
      <ProductBuy/>
      <ProductComment/>
    </div>
</template>

<script>
  import ProductImg from "@/components/ProductDetail/ProductImg.vue"
  import ProductBuy from "@/components/ProductDetail/ProductBuy.vue"
  import ProductComment from "@/components/ProductDetail/ProductComment.vue"
    export default {
        name: "ProductDetail",
      components:{
        ProductImg,
        ProductBuy,
        ProductComment
      }
    }
</script>

<style scoped>

</style>
