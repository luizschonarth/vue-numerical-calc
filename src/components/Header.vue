<template>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>
  </div>
</template>

<script>
export default {
  name: "Header",
  components: {},
};
</script>

<style scoped>
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
</style>
