<template>
  <div class="home">
    <h1>Vue Numerical Calculator</h1>
  </div>
  <Methods />
</template>

<script>
import Methods from "../components/Methods.vue";

export default {
  name: "Home",
  components: {
    Methods,
  },
};
</script>
