<template>
  <div class="view">
    <div class="container">
      <div class="signUp">
        <h3>sign up now!</h3>
      </div>
      <div class="social">
        <h3>Follow Us</h3>
        <img src="../assets/img/footer-facebook.png" alt="" />
        <img src="../assets/img/footer-twitter.png" alt="" />
        <img src="../assets/img/footer-youtube.png" alt="" />
        <img src="../assets/img/footer-pinterest.png" alt="" />
        <img src="../assets/img/footer-periscope.png" alt="" />
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
  background-color: #303030;
}

.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.signUp {
  border: 2px solid $mainColor;
}
h3 {
  color: white;
  padding: 10px;
  text-transform: uppercase;
}

.social {
  display: flex;
  justify-content: space-around;
  align-items: center;

  h3 {
    text-transform: uppercase;
    color: $mainColor;
  }

  img {
    height: 30px;
    margin: 10px;
  }
}
</style>