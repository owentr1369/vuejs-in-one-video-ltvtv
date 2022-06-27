<template>
  <div class="container">
    <input type="text" v-model="name" />
    <h1>{{ name }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return { name: "Tran Thien Tam" };
  },
};
</script>

<style>
</style>