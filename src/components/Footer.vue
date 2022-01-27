<template>
  <div>
    <FooterItem />
    <FooterMenu />
    <FooterSocial />
  </div>
</template>

<script>
import FooterItem from './FooterItem.vue'
import FooterMenu from './FooterMenu.vue'
import FooterSocial from './FooterSocial.vue'

export default {
  name: 'Footer',
  components:{
    FooterItem,
    FooterMenu,
    FooterSocial
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

</style>
