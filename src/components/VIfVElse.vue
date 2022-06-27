<template>
  <div>
    <h1 v-if="show">Show</h1>
    <h2 v-else>Hide</h2>
    <button @click="isShow">Switch</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      show: true,
    };
  },
  methods: {
    isShow: function () {
      this.show = !this.show;
    },
  },
};
</script>

<style>
</style>