<template>
  <div class="hello">
    <h1>{{ msg }}</h1>

    <h3>Essential Links</h3>
    <ul>
      <li><a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a></li>
      <li><a href="https://forum.vuejs.org" target="_blank" rel="noopener">Forum</a></li>
      <li><a href="https://chat.vuejs.org" target="_blank" rel="noopener">Community Chat</a></li>
      <li><a href="https://twitter.com/vuejs" target="_blank" rel="noopener">Twitter</a></li>
      <li><a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a></li>
    </ul>
  </div>



  <div id="app">
  <nav class="mainNav">
  <img src="https://github.com/jannaee/PP3/blob/master/pool-pro-app/src/assets/pool-pros-logo.png?raw=true" alt="pool pros logo"/>
  
  <button><img src=""/></im>FIND A PRO</button>
  </nav>

</div>

</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../css/components/main.scss";
</style>
