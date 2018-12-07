<template>
  <div class="home">
    <HeaderNav/>
    <!-- Add in the filter component next -->
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
