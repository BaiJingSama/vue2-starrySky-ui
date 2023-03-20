<template>
  <div id="app">
    <gButton></gButton>
  </div>
</template>

<script>
import gButton from './components/g-button'

export default {
  name: 'App',
  components: {
    gButton
  }
}
</script>

<style lang="scss">
@import './assets/style/reset.scss';
@import './assets/style/vars.scss';
body{
  font-size: $font-size;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
