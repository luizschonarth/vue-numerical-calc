<!-- This is a single method -->
<template>
  <div class="method">
    <h1>{{ msg }}</h1>
  </div>
</template>

<style scoped>
.method {
  margin: auto;
  /* This values are just placeholders */
  width: 200px;
  height: 200px;
  /* This values are just placeholders */
  background-color: #3d405d;
  border-radius: 10px;
  color: white;
}
</style>

<script>
export default {
  name: "Method",
  props: {
    msg: String,
  },
  components: {},
};
</script>
