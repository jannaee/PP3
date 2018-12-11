<template>
  <main>
    <ul class="dealer-cards">
      <li v-for='(card , index) in cards' :key='index'>
        <!-- <h2>{{ cards.location }}</h2>
        <p>{{cards.zipcode}}</p> -->
        <p>{{ cards.dealers[0].data.name }}</p>

      </li>
    </ul>
  </main>
</template>
<script>
import json from '../data/dealers.json'
export default {
  data () {
    return {
      cards: json
    }
  }
}
</script>

<style lang="scss">
  .dealer-cards {
    li {
      list-style-type: none;
      border: 1px solid #000000;
      display: inline-flex;
      flex-direction: row;
      padding: 30px;
      margin: 20px;
      width: 100px;
      border-radius: 2px;
      box-shadow: 2px 2px 2px rgba(0,0,0, .2);

    }

  }
</style>
