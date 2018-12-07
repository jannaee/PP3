<template>
  <div class="home">
    <HeaderNav msg="The start of something beautiful"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderNav from '@/components/HeaderNav.vue'

export default {
  name: 'home',
  components: {
    HeaderNav
  }
}
</script>
