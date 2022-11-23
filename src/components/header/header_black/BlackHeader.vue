<template>
  <div>
    <div class="dark">
      <div id="header-container-black">
        <h2> --> Contents goes here </h2>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "BlackHeader",
  components: {},
};
</script>

<style lang="scss" scoped>
#header-container-black {
  width: 75%;
  // padding: 10px 0;
  background-color: #1c1c1c;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: space-between;

  h2{
   color: white;
  }

}

.dark{
  height: 15vh;
  display: flex;
  align-items: center;
  background-color: #1c1c1c;
}

</style>