<template>
  <div id="app">
    <h1>VueJS LTV TV</h1>
    <two-ways-binding />
  </div>
</template>

<script>
import TwoWaysBinding from "./components/TwoWaysBinding.vue";
export default {
  name: "App",
  components: { TwoWaysBinding },
};
</script>

<style>
#app {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  min-height: 100vh;
  flex-direction: column;
}
</style>
