<template>
  <div id="app">
    <NewsReader />
  </div>
</template>

<script>
import NewsReader from './components/NewsReader.vue'

export default {
  name: 'App',
  components: {
    NewsReader
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

查看全部
