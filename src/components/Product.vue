<template>
  <div class="product">
    <div class="immagine">
      <img :src="prodotto.thumb" :alt="prodotto.series" />
    </div>

    <h5>{{ prodotto.series }}</h5>
  </div>
</template>

<script>
export default {
  name: "Product",
  props: {
    prodotto: Object,
  },
};
</script>

<style lang="scss" scoped>
.product {
  width: 180px;
  margin: 20px 0;

  display: inline-block;
  .immagine {
    height: 170px;
    text-align: center;
    


    img {
      height: 170px;
    }
  }
  h5 {
      color: white;
      text-align: center;
      text-transform: uppercase;
      padding: 10px 0;

  }
}
</style>
© 2022 GitHub, Inc.