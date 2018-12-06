<template>
  <div class="home">
    <img alt="Pool Pros Logo" src="../assets/pool-pros-logo.png">
    <HelloWorld msg="The start of something beautiful"/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
