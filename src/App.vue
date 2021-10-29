<template>
  <Header />
  <router-view />
  <Footer />
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";

export default {
  name: "App",
  components: {
    Header,
    Footer,
  },
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
</style>
