<template>
   <div>
      <div id="bg-container">
         <div id="sized-container">
            <div class="flex">
               <div>
                  <ul>
                     <li class="title">DC COMICS</li>
                     <li>Characters</li>
                     <li>Comics</li>
                     <li>Movies</li>
                     <li>TV</li>
                     <li>Games</li>
                     <li>Videos</li>
                     <li>News</li>
                  </ul>
                  <ul>
                     <li class="title">SHOP</li>
                     <li>Shop DC</li>
                     <li>Shop DC Collectibles</li>
                  </ul>
               </div>
               <div>
                  <ul>
                     <li class="title">DC</li>
                     <li>Therms Of Use</li>
                     <li>Privacy policy (New)</li>
                     <li>Ad Choises</li>
                     <li>Advertising</li>
                     <li>Jobs</li>
                     <li>Subscriptions</li>
                     <li>Talent Workshops</li>
                     <li>CPSC Certificates</li>
                     <li>Ratings</li>
                     <li>Shop Help</li>
                     <li>Contact Us</li>
                  </ul>
               </div>
               <div>
                  <ul>
                     <li class="title">SITES</li>
                     <li>DC</li>
                     <li>MAD Magazine</li>
                     <li>DC Kids</li>
                     <li>DC Univese</li>
                     <li>DC Power Visa</li>
                  </ul>
               </div>
            </div>

            <div id="img-container">
              <img id="blue-logo" src="../../../assets/img/dc-logo-bg.png" alt="logo">
            </div>
            
         </div>
      </div>
   </div>
</template>

<script>
   export default {
      name: 'MainAboutUs'
   }
</script>

<style lang="scss" scoped>
#bg-container{
   background-image: url(../../../assets/img/footer-bg.jpg);
   background-repeat: no-repeat;
   background-size: cover;
   height: 370px;
}

#sized-container{
   width: 75%;
   margin: 0 auto;
   display: flex;
   align-items: center;
   justify-content: space-between;
   color: #706D71;
   text-align: left;
}

ul{

   li{
      list-style-type: none;
   }

}

.flex{
   display: flex;
}

.title{
   font-weight: 800;
   font-size: 1.3rem;
   margin-bottom: 10px;
   color: white;
}

#img-container{
   width: 370px;
   height: 370px;
   img{
      width: 100%;
   }
}
</style>