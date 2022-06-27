<template>
  <div id="app">
    <h1>VueJS LTV TV</h1>
    <!-- <two-ways-binding /> -->
    <!-- <v-show /> -->
    <!-- <v-if-v-else /> -->
    <event-listener />
  </div>
</template>

<script>
// import TwoWaysBinding from "./components/TwoWaysBinding.vue";
// import VShow from "./components/VShow.vue";
// import VIfVElse from "./components/VIfVElse.vue";
import EventListener from "./components/EventListener.vue";

export default {
  name: "App",
  components: { EventListener },
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
