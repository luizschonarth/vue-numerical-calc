<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
  <Methods />
</template>

<script>
import Methods from "./components/Methods.vue";

export default {
  name: "App",
  components: {
    Methods,
  },
};
</script>

<style>
* {
  margin: 0px;
  padding: 0px;
}

html {
  scroll-behavior: smooth;
}

body {
  background-color: #f4f1de;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  user-select: none;
  background-color: #e07a5f;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
