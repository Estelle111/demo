<template>
  <div id="app">
    <appHeader></appHeader>
    <appTalents></appTalents>
  </div>
</template>

<script>
import header from './components/header.vue';
import talents from './components/talents.vue';

export default {
  name: 'app',
  components: {
    appHeader:header,
    appTalents:talents
  },
  data() {
    return {

    }
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
  background-image: url("assets/fruit.png");
  background-repeat: no-repeat;
  background-position: center;
}
</style>
