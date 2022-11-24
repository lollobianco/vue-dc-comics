<template>
  <div>
    <div class="dark">
      <div id="header-container-jumbo">

        
      
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
}

.dark{
  display: flex;
  align-items: center;
  background-color: #1c1c1c;
}

</style>