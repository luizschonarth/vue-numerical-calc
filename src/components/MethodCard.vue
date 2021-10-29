<!-- This is a single method -->
<template>
  <div class="method">
    <h1>{{ methodName }}</h1>
  </div>
</template>

<script>
export default {
  name: "MethodCard",
  props: {
    methodName: String,
  },
  components: {},
};
</script>

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
