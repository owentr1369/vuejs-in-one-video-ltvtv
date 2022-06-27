<template>
  <div class="container">
    <form>
      <h1>{{ heading }}</h1>
      <button @click.prevent="heading = 'Hi!'">Change</button>
    </form>
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