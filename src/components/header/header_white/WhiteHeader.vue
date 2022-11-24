<template>
   <div>
      <div id="header-container">
         <img src="../../../assets/img/dc-logo.png" alt="">

         <NavHeader/>
      </div>
   </div>
</template>

<script>
import NavHeader from './NavHeader.vue'

   export default {
      name: 'WhiteHeader',
      components: {
         NavHeader
      }
   }
</script>

<style lang="scss" scoped>

#header-container{
   width: 75%;
   margin: 0 auto;
   display: flex;
   align-items: center;
   justify-content: space-between;
}

</style>