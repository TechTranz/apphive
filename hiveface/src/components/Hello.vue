<template>
  <div class="hello">
    <h1>{{ welcome }}</h1>
    <img src="../assets/logo.png" alt="Apphive Logo">  
    <h1>Apphive Hiveface</h1>
    <h2>{{ tagline }}</h2>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      welcome: 'Welcome !!!',
      tagline: 'Face of the Apphive'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
h1, h2 {
  font-weight: normal;
}

h2 {
  font-style: italic;
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
  color: #35495E;
}
</style>
