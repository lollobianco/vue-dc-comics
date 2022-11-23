<template>
   <div>
      <ul class="flex">
         <li>CHARACTERS</li>
         <li class="active">COMICS <div class="underline"></div> </li>
         <li>MOVIES</li>
         <li>TV</li>
         <li>GAMES</li>
         <li>COLLECTIBLES</li>
         <li>VIDEOS</li>
         <li>FANS</li>
         <li>NEWS</li>
         <li>SHOP</li>
      </ul>
   </div>
</template>

<script>
   export default {
      name: 'NavHeader'
   }
</script>

<style lang="scss" scoped>

ul{
   display: flex;
   li{
      list-style-type: none;
      font-size: 0.8rem;
      margin: 0 10px;
      font-weight: 700;
   }
}

.active{
   color: #0282F9;
   position: relative;
   height: 100%;
}

.underline{
   width: 100%;
   border: 1px solid #0282F9;
   position: absolute;
   bottom: -66px;
}

</style>