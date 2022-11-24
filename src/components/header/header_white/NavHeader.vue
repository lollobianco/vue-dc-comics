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
   margin: 0;
   li{
      list-style-type: none;
      font-size: 0.8rem;
      font-weight: 700;
      margin: 0 10px;
      padding: 50px 0;
   }
}

.active{
   color: #0282F9;
   border-bottom: 3px solid #0282F9;
}


</style>