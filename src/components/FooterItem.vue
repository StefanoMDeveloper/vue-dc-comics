<template>
  <div class="view">
    <div class=" container footer-container">
      <div class="item">
        <div>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        </div>
        <p class="item-title">digital comics</p>
      </div>
      <div class="item">
        <div>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        </div>
        <p class="item-title">digital comics</p>
      </div>
      <div class="item">
        <div>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        </div>
        <p class="item-title">digital comics</p>
      </div>
      <div class="item">
        <div>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        </div>
        <p class="item-title">digital comics</p>
      </div>
      <div class="item">
        <div>
          <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
        </div>
        <p class="item-title">digital comics</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterItem",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../assets/style/partials/variables.scss";
.view {
  background-color: $mainColor;

  .footer-container {
    display: flex;
    justify-content: space-evenly;

    .item {
      display: inline-flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 10px;
    }
  }
}

img {
  height: 50px;
}

p {
  color: white;
  text-transform: uppercase;
  vertical-align: middle;
  display: inline-block;
  font-size: 12px;
  margin-left: 15px;
}
</style>