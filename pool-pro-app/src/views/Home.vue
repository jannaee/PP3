<template>
  <main>
    <ul class="container">
      <li class="dealer-cards" v-for='(card , index) in cards' :key='index'>
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
  .container {
    display: inline-flex;
    flex-flow: row;
    justify-content: center;
    background-color:#000000;

  }
  .dealer-cards {
      list-style-type: none;
      border: 1px solid #000000;
      padding: 30px;
      height: 40vh;
      margin: 5px;
      width: 15vw;
      border-radius: 6px;
      box-shadow: 2px 2px 2px rgba(0,0,0, .2);
  }
</style>
