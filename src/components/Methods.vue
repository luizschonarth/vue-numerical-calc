<!-- This is where all methods cards are contained -->
<template>
  <div class="methods">
    <h2>This is a component to contain the methods</h2>
    <Method msg="Hi!" />
    <Method msg="I" />
    <Method msg="am" />
    <Method msg="a" />
    <Method msg="Method" />
  </div>
</template>

<script>
import Method from "./Method.vue";

export default {
  name: "Methods",
  components: {
    Method,
  },
};
</script>

<style scoped>
.methods {
  margin: auto;
  display: flex;
  flex-direction: column;
  /* This values are just placeholders */
  width: 1000px;
  height: 700px;
  /* This values are just placeholders */
  border-radius: 10px;
  border: 1px solid rgb(226, 100, 100);
}
</style>
