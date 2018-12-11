<template>
  <main>
    <ul>
      <li v-for='(card,index) in cards' :key='index'>
        <h2>{{ cards.zipcode }}</h2>
        <p>{{ card.phone }}</p>
        <p>{{ card.email }}</p>
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
