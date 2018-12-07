<template>
  <nav class="mainNav">
    <img src="../assets/pool-pros-logo.png" alt="pool pros logo"/>
    <button><img src="../assets/location-icon.png" class="icon-location"/>FIND A PRO</button>
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
@import "../css/components/home.scss";
</style>
