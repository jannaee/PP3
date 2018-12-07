<template>
  <nav class="mainNav">
    <img src="../assets/pool-pros-logo.png" alt="pool pros logo"/>
    <button><img src="../assets/location-icon.png" class="icon-location"/>FIND A PRO</button>
    <img src="../assets/menu-icon-mobile.png" class="icon-mobile-nav" alt="Navigation menu icon" />

  </nav>
</template>

<script>
export default {
  name: 'HeaderNav',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../css/main.scss";
</style>
