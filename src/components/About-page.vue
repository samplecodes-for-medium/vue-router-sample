<template>
  <div>
    <img width="25%" src="../assets/logo.png">
    <h1>About Page</h1>
    <h2>It is me, Ercan...</h2>
    <h3>Router:</h3>
    <a @click="routeToHomePage">Go to Home</a>
  </div>
</template>
<script>
import router from "../routes";
export default {
  name: "About-page",
  methods: {
    routeToHomePage() {
      router.push("home");
    }
  }
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
