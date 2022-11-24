<template>
   <div id="main-comp">
      <MainBlue/>
      <MainAboutUs/>
      <DcCard/>
   </div>
</template>

<script>
import MainBlue from './main_blue/MainBlue.vue'
import MainAboutUs from './main_aboutus/MainAboutUs.vue'
import DcCard from './main_cards/DcCard.vue'

   export default {
      name: 'MainComp',
      components: {
         MainBlue,
         MainAboutUs,
         DcCard
      }
   }
</script>

<style lang="scss" scoped>
#main-comp{
height: 60vh;
}
</style>