<template>
  <main>
    <ul>
      <li class='listItem' v-for='(card,index) in cards' :key='index'>
        <h2>{{ card.title }}</h2>
        <p>{{ card.phone }}</p>
        <p>{{ card.email }}</p>
      </li>
    </ul>
  </main>
</template>
<script>
import json from './json/data.json'
export default {
  data () {
    return {
      cards: [
        {
          title: 'Aqua Experts',
          phone: '1321',
          email: 'you@gmail.com'
        },
        {
          title: 'PP Pools',
          phone: '1321',
          email: 'you@gmail.com'
        },
        {
          title: 'Carolina Pool Specialists',
          phone: '1321',
          email: 'you@gmail.com'
        }
      ]
    }
  }
}
</script>
