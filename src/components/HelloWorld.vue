<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Connect with Me</h3>
    <ul>
      <li><a href="https://github.com/ashishjsharda/" target="_blank" rel="noopener">GitHub</a></li>
      <li><a href="https://rpubs.com/ashishjsharda/" target="_blank" rel="noopener">RPubs</a></li>
    </ul>
    
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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
