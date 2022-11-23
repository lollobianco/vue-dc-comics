<template>
  <div>
    <div class="blue-bg center-full">
      <div id="blue-section-container" class="center-full">
        <div class="center">
          <img
            class="image"
            src="../../../assets/img/buy-comics-digital-comics.png"
            alt="Digital Comics"
          />
          <span>DIGITAL COMICS</span>
        </div>

        <div class="center">
          <img
            class="image"
            src="../../../assets/img/buy-comics-merchandise.png"
            alt="Digital Comics"
          />
          <span>DC MERCHANDISE</span>
        </div>

        <div class="center">
          <img
            class="image"
            src="../../../assets/img/buy-comics-subscriptions.png"
            alt="Digital Comics"
          />
          <span>SUBSRIPTION</span>
        </div>

        <div class="center">
          <img
            class="image image-locator"
            src="../../../assets/img/buy-comics-shop-locator.png"
            alt="Digital Comics"
          />
          <span>COMIC SHOP LOCATOR</span>
        </div>

        <div class="center">
          <img
            class="image image-svg"
            src="../../../assets/img/buy-dc-power-visa.svg"
            alt="Digital Comics"
          />
          <span>DC POWER VISA</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainBlue",
};
</script>

<style lang="scss" scoped>
.blue-bg {
  background-color: #0282f9;
  height: 15vh;
  color: white;
}

#blue-section-container {
  width: 75%;
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: center;
}

.image {
  width: 20%;
  margin-right: 20px;
}

.image-svg {
  width: 15%;
}

.image-locator {
  width: 15%;
}

.center {
  display: flex;
  align-items: center;
  justify-content: center;
}

.center-full {
  display: flex;
  align-items: center;
  justify-content: center;
}

span {
  font-size: 0.9rem;
}
</style>