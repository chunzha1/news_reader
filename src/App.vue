<template>
  <div id="app">
    <NewsReader />
    <Heart />
  </div>
</template>

<script>
import NewsReader from './components/NewsReader.vue'
import MyImage from './components/Heart.vue'

export default {
  name: 'App',
  components: {
    NewsReader,
    Heart
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
