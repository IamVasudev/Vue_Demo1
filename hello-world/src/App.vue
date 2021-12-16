<template>
  <div id="app">
    <h1>hello {{ name }}</h1>
    <div>{{ phone }}</div>
    <div v-html="hl"></div>
  </div>
</template>

<script>
export default {
  name: "App",
  data() {
    return {
      name: "batman",
      hl: "<b>123123</b>",
      phone: "234234",
    };
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
