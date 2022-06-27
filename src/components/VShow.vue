<template>
  <div class="container">
    <h1 v-show="isShow">Hello</h1>
    <button @click="show">Show/Hide</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isShow: false,
    };
  },
  methods: {
    show: function () {
      this.isShow = !this.isShow;
    },
  },
};
</script>

<style>
</style>