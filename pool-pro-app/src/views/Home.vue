<template>
  <main>
    <ul>
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
