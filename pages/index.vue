<template>
  <main class="index">
    <header>
      <h1>Developers with an attitude</h1>
    </header>
    <section class="hero">
      <ul>
        <li>
          <img src="~/assets/img/elian.png" />
          <h2>Elian Van Cutsem</h2>
          <a href="https://www.twitter.com/vancutsemelian" target="_blank">@vancutsemelian</a>
          <a href="https://www.elian.codes" target="_blank">www.elian.codes</a>
        </li>
        <li>
          <img src="~/assets/img/dries.jpeg" />
          <h2>Dries Bruggeman</h2>
          <a href="#" target="_blank">@dries.bruggeman</a>
          <a href="http://www.driesbruggeman.software/" target="_blank">www.driesbruggeman.software</a>
        </li>
        <li>
          <img src="~/assets/img/aaron.jpeg" />
          <h2>Aaron Lison</h2>
          <a href="#" target="_blank">@aaron.lison</a>
          <a href="https://www.stackoverflow.com" target="_blank">www.stackoverflow.com</a>
        </li>
      </ul>
    </section>
  </main>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'index',
  head: {
    title: 'Home | Developers With an Attitude'
  }
})
</script>
