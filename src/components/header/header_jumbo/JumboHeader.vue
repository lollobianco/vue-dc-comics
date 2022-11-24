<template>
  <div>
    <div class="dark">
      <div id="header-container-jumbo">

        <div id="button-container">
          <button class="button">CURRENT SERIES</button>
        </div>

        
      
      </div>
    </div>
  </div>
</template>

<script>

export default {
  name: "JumboHeader",
  components: {

  },
};
</script>

<style lang="scss" scoped>
#header-container-jumbo {
  width: 100%;
  background-image:url(../../../assets/img/jumbotron.jpg);
  background-size: cover;
  background-repeat: no-repeat;
  height: 350px;
  position: relative;
  
}

.dark{
  display: flex;
  align-items: center;
  background-color: #1c1c1c;
}

#button-container{
  width: 75%;
  margin: 0 auto;
  text-align: left;
  position: absolute;
  bottom: -25px;
  left: 230px;
}

.button{
   padding: 15px 50px;
   border: 0;
   background-color: #0282F9;
   color: white;
   font-weight: 800;
   font-size: 1rem;
   margin-top: 30px;
}

</style>