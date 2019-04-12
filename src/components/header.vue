<template>
  <header>
    <h2>{{smTitle}}</h2>
    <hr>
    <hr>
    <h1>{{title}}</h1>
  </header>
</template>

<script>
  export default {
    data() {
      return {
        smTitle: "10 things that require",
        title: "zéro talent"
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  body {
    background-color: black;
  }
  h1, h2 {
    color: white;
    text-transform: uppercase; 
  }
  h2 {
    font-size: 40px;
    margin-bottom: 0;
  }
  h1 {
    font-size: 75px;
    margin-top: 0;
  }
  hr {
    width: 500px;
    color: white;
  }
</style>