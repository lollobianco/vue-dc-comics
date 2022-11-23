<template>
   <div id="main-comp">
      <MainBlue/>
      <MainAboutUs/>
   </div>
</template>

<script>
import MainBlue from './main_blue/MainBlue.vue'
import MainAboutUs from './main_aboutus/MainAboutUs.vue'

   export default {
      name: 'MainComp',
      components: {
         MainBlue,
         MainAboutUs
      }
   }
</script>

<style lang="scss" scoped>
#main-comp{
height: 60vh;
}
</style>