<template>
  <div class= "view">
    <MainJumbo />
    <MainProducts />
  </div>
</template>

<script>
import MainJumbo from './MainJumbo.vue'
import MainProducts from './MainProducts.vue'

export default {
  name: 'Main',
  components:{
    MainJumbo,
    MainProducts
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .view{
    background-color: #1c1c1c;
    min-height: 200px;
    padding: 0px;
  }

  h1{
    color: white;
  }
</style>
