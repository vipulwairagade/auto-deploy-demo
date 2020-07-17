<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Auto Deploy Vue.js/React.js/Angular application to Github Pages using Github Actions</h2>
    <h3>Thanks for watching our video</h3>
    <h3>If you found it useful do Like the video and Subscribe us for more content updates</h3>
    <h3>Also, share your views in the comments section</h3>
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
