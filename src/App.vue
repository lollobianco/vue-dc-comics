<template>
  <div id="app">
    <HeaderComp/>
    <MainComp/>
    <FooterComp/>
  </div>
</template>

<script>
import HeaderComp from './components/header/header_white/HeaderComp.vue'
import MainComp from './components/main/MainComp.vue'
import FooterComp from './components/footer/FooterComp.vue'


export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    FooterComp
  }
}
</script>


<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  color: #2c3e50;
}

*{
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}
</style>
