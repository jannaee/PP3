<template>
  <div id="app">
    <TheHeaderNav></TheHeaderNav>
    <router-view/>
    <h1>Footer</h1>
  </div>
</template>
<script>
import TheHeaderNav from '@/components/TheHeaderNav.vue'

export default {
  components: {
    TheHeaderNav
  }
}
</script>

<style scoped lang="scss">
@import "@/css/main.scss";
</style>
