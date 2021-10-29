<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
  <router-view />
  <footer id="footer">
    <h1>This is a healthy footer</h1>
  </footer>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
:root {
  --color-primary-dark: #2c3e50;
  --color-primary-light: #f4f1de;
  --color-primary-orange: #e07a5f;
}

* {
  margin: 0px;
  padding: 0px;
}

html {
  scroll-behavior: smooth;
}

body {
  background-color: var(--color-primary-light);
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

#nav {
  padding: 30px;
  user-select: none;
  background-color: var(--color-primary-orange);
}

#nav a {
  font-weight: bold;
  color: var(--color-primary-dark);
  text-decoration: none;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

#footer {
  background-color: var(--color-primary-dark);
  color: white;
}
</style>
