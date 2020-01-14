<template>
  <div>
    <img width="25%" src="../assets/logo.png">
    <h1>Home Page</h1>
    <h2>Welcome to Home Page</h2>
    <h3>Router:</h3>
    <router-link to="/about">Go to About</router-link>
  </div>
</template>
<script>
export default {
  name: "Home-page"
};
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
