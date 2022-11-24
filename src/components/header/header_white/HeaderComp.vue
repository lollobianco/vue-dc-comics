<template>
   <div id="header-comp">
      
      <WhiteHeader/>
      <JumboHeader/>
      
   </div>
</template>

<script>
import WhiteHeader from './WhiteHeader.vue'
import JumboHeader from '../header_jumbo/JumboHeader.vue'


   export default {
      name: 'HeaderComp',
      components: {
         WhiteHeader,
         JumboHeader
         
      }
   }
</script>

<style lang="scss" scoped>

</style>