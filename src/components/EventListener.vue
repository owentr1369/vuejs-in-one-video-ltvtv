<template>
  <div class="container">
    <h1>{{ heading }}</h1>
    <button @mouseover="heading = 'Hi!'">Change</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      heading: "Hello",
    };
  },
};
</script>

<style>
</style>