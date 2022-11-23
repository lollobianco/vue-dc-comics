<template>
   <div>
      
      <WhiteHeader/>
      <BlackHeader/>
      
   </div>
</template>

<script>
import WhiteHeader from './WhiteHeader.vue'
import BlackHeader from '../header_black/BlackHeader.vue'


   export default {
      name: 'HeaderComp',
      components: {
         WhiteHeader,
         BlackHeader
         
      }
   }
</script>

<style lang="scss" scoped>

</style>