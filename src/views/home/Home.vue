<template>
  <div class='home'>
    <nav-bar class = 'nav-bar'><div slot="center">购物街</div></nav-bar>
  </div>
</template>

<script>
import NavBar from '../../components/common/navbar/NavBar.vue'
export default {
  components: {
    NavBar
  }

}
</script>
<style scoped>
.nav-bar{
  background-color: var(--color-tint);
  color: white
}

</style>
