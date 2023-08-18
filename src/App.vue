<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <h1>This is App.vue</h1>
  <p>{{ message }}</p>

  <div>
    <form>
      <input type="text">
      <button>Add</button>
    </form>
  </div>
</template>

<script>
export default {
  data: () => ({
    message: "Hello Vue.js"
  })
}
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
