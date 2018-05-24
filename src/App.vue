<template>
  <div id="app">
    <Home/>
  </div>
</template>

<script>
import Home from "./containers/Home.vue";

export default {
  name: "app",
  components: {
    Home
  },
  data() {
    return {
      msg: "Welcome to Your Vue.js App"
    };
  }
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Open+Sans|Raleway");

/* font-family: 'Raleway', sans-serif;
font-family: 'Open Sans', sans-serif; */

* {
  font-family: "Raleway", sans-serif;
  margin: 0;
  padding: 0;
}

a {
  text-decoration: none;
  color: black;
}
</style>
