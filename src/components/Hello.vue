<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Essential Links</h2>
    <ul class="tab-group">
      <li class="tab active"><a href="#signup">Sign Up</a></li>
      <li class="tab"><a href="#login">Log In</a></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data() {
    return {
      msg: 'this is the hello componenent',
    };
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

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
