// src/App.vue

<template lang="pug">
.container
	h1 {{ message }}
</template>

<style lang="stylus" scoped>
.container
	width: 600px;
	margin: 50px auto;
	text-align: center;
</style>

<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Using Parcel In A Vue.js App',
    };
  },
};
</script>
