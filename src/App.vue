<template>
  <div id="app">
    <ApartSearch/>
  </div>
</template>

<script>
import ApartSearch from './components/ApartSearch.vue'

export default {
  name: 'App',
  components: {
    ApartSearch
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
