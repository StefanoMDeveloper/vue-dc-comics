<template>
  <div class="view">
    <div class="container header-container">
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <nav>
        <ul>
          <li v-for = "(element, index) in links" :key= "index">
            <a href="element.url" :class= "{'active': element.current}">{{element.text}}</a>
          </li>
        </ul>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        {
          text: "characters",
          url: "#",
          current: true,
        },
        {
          text: "comics",
          url: "#",
          current: false,
        },
        {
          text: "movies",
          url: "#",
          current: false,
        },
        {
          text: "tv",
          url: "#",
          current: false,
        },
        {
          text: "games",
          url: "#",
          current: false,
        },
        {
          text: "collectibles",
          url: "#",
          current: false,
        },
        {
          text: "videos",
          url: "#",
          current: false,
        },
        {
          text: "fans",
          url: "#",
          current: false,
        },
        {
          text: "news",
          url: "#",
          current: false,
        },
        {
          text: "shop",
          url: "#",
          current: false,
        },
      ],
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

@import '../assets/style/partials/variables.scss';

.view {
  width: 100%;
  height: 100px;
  padding: 20px;
}
.header-container{
  display: flex;
  justify-content: space-between;

}
.logo{
  display: inline-block;

  img{
    height: 60px;
  }
}
header{
  text-align: center;
}
nav{
  ul{
    list-style-type: none;
    display: flex;
    justify-content: center;
    li a{
      text-transform: uppercase;
      font-size: 12px;
      display: inline-block;
      color: black;
      padding: 15px 12px;
      text-decoration: none;
   
      // nav ul li a.active, nav ul li a:hover 
      &.active, &:hover{
        border-bottom: 2px solid $mainColor;
      }
    }
  }
}
</style>
