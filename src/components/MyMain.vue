<template>
  <div id="main">
    <h2> ..Content goes here.. </h2>
  </div>
</template>

<script>
export default {
  name: 'MyMain',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
  #main {
    background-color: black;
    padding: 15px 15%;
    min-height: 50px;
  }
  h2 {
    color: white;
  }
</style>
