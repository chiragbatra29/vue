<!-- <template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style> -->
<!-- <script src="https://unpkg.com/vue"></script> -->
<template>
  <div id="app">
    <span v-bind:title="message">
      Hover your mouse over me for a few seconds
      to see my dynamically bound title!
    </span>
  </div>
</template>
