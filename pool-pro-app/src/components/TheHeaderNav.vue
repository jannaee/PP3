<template>
  <nav class="main-header-nav" id="main-nav">
    <a href><img src="../assets/pool-pros-logo.png" alt="pool pros logo"></a>
    <a href="#">Pools & Spas</a>
    <a href="#">Supplies</a>
    <a href="#">Resources</a>
    <a href="#">Service</a>
     <button>
      <img src="../assets/location-icon.png" class="icon-location">FIND A PRO
    </button>
    <a @click.stop="expandNav()">
      <img src="../assets/menu-icon-mobile.png" class="icon-mobile-nav mobile" alt="Navigation menu icon">
    </a>
  </nav>
</template>

<script>
export default {
  name: 'TheHeaderNav'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  @import "../css/main.scss";
</style>
