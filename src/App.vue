<template>
  <div id="app">
    <vue-mescroll>
      <div slot="down-html-content">sssefe</div>
      <div v-for="i in 100">{{i}}</div>
    </vue-mescroll>
  </div>
</template>

<script>
import VueMescroll from '../vue-mescroll'

export default {
  name: 'App',
  components: {
    VueMescroll
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
