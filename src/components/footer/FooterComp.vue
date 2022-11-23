<template>
   <div id="footer-comp">
      <div id="footer-container">

         <div>
            <button class="button">SIGN-UP NOW</button>
         </div>

         <div id="follow-us">
            <div>FOLLOW US</div>
            <img src="../../assets/img/footer-facebook.png" alt="logo" class="logo">
            <img src="../../assets/img/footer-twitter.png" alt="logo" class="logo">
            <img src="../../assets/img/footer-youtube.png" alt="logo" class="logo">
            <img src="../../assets/img/footer-pinterest.png" alt="logo" class="logo">
            <img src="../../assets/img/footer-periscope.png" alt="logo" class="logo">
         </div>

      </div>
   </div>
</template>

<script>
   export default {
      name: 'FooterComp'
   }
</script>

<style lang="scss" scoped>

#footer-comp{
   width: 100%;
   height: 10vh;
   background-color: #303030;
   display: flex;
   align-items: center;
   justify-content: space-between;
}

#footer-container{
   width: 75%;
   margin: 0 auto;
   display: flex;
   align-items: center;
   justify-content: space-between;
}

.button{
   padding: 10px 15px;
   border: 2px solid #0085FF; 
   background-color: #303030;
   color: white;
}

#follow-us{
   display: flex;
   justify-content: space-between;
   align-items: center;
   div{
      color: #0085FF;
      font-weight: 800;
      font-size: 1.3rem;
      margin-right: 10px;
   }
}

.logo{
   margin-right:10px ;
}

</style>