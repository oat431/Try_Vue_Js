<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      Hi, I am Sahachan And I heard that This semester I will learn Vue so <br>
      Let do vue shall we? 
      <a href="https://github.com/oat431" target="_blank" rel="noopener">My work and backup Btw</a>.
    </p>
    
  </div>
</template>

<script>
export default {
  name: 'Sahachan Tippimwong',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
