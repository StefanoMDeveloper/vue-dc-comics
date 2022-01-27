<template>
  <div class="view">
    <div class="container">
      <div>
        <div class="left">
          <ul>
            <h3>Dc comics</h3>
            <li>Characters</li>
            <li>Comics</li>
            <li>Movies</li>
            <li>Tv</li>
            <li>Games</li>
            <li>Videos</li>
            <li>News</li>
          </ul>
          <ul>
            <h3>shop</h3>
            <li>Shop DC</li>
            <li>Shop DC collectibles</li>
          </ul>
        </div>

        <div class="left">
          <ul>
            <h3>DC</h3>
            <li>Term Of Use</li>
            <li>Privacy policy (New)</li>
            <li>Ad Choises</li>
            <li>Advertising</li>
            <li>Jobs</li>
            <li>Subscription</li>
            <li>Talent Workshop</li>
            <li>CPSC Certificates</li>
            <li>Ratings</li>
            <li>Shop Help</li>
            <li>Among Us</li>
          </ul>
        </div>
        <div class="left">
          <ul>
            <h3>sites</h3>
            <li>DC</li>
            <li>MAD Magazine</li>
            <li>DC Kids</li>
            <li>DC Universe</li>
            <li>DC Power Visa</li>
          </ul>
        </div>
      </div>

    <div>
        <img src="../assets/img/dc-logo-bg.png" alt="">
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
  background-image: url("../assets/img/footer-bg.jpg");
  height: 360px;
  overflow: hidden;
}

.container{
    display: flex;
    justify-content: space-between;
}

.left {
  float: left;
  padding: 10px;
}

ul {
  list-style-type: none;
  padding: 5px;
  h3 {
    color: white;
    text-transform: uppercase;
    margin-bottom: 10px;
  }

  li {
    color: darkgray;
    font-size: 13px;
    padding: 3px;
  }
}

img{
    transform: translate(0,-25%);
}
</style>