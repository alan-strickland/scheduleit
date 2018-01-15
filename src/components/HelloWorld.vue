<template>
  <v-layout column align-center>
    <img src="/static/v.png" alt="Vuetify.js" class="mb-5" />
    <blockquote>
      &#8220;{{ quote }}&#8221;
      <footer>
        <small>
          <em>&mdash;{{ author }}</em>
        </small>
      </footer>
    </blockquote>
  </v-layout>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      quote: 'First, solve the problem. Then, write the code.',
      author: 'John Johnson'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
