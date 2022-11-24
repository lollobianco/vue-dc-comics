<template>
   <div class="card">
      
      <div class="img-container">
         <img :src="productDetails.thumb" alt="ProductImage">
      </div>
      

      <div class="detail">{{productDetails.series.toUpperCase()}}</div>
      
   </div>
</template>

<script>
   export default {
      name: 'DcCard',
      props:{
         productDetails: Object
      }
   }
</script>

<style lang="scss" scoped>

.card{
   width: calc(100%/6);
   padding: 20px 0;
   text-align: left;
   color: white;
   font-weight: 700;
   font-size: 0.8rem;
}

.img-container{
   width: 85%;
   margin: 0 auto;

   img{
      width: 100%;
      aspect-ratio: 1/1;
      object-fit:cover;
      object-position: top;
   }

}

.detail{
   width: 85%;
   margin: 0 auto;
}

</style>