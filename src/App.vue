<template>
  <div class="container">
    <HeaderComponent msg="Task Tracker"/>
  </div>
</template>

<script>
import HeaderComponent from './components/Header.vue'

export default {
  name: 'App',
  components: {
    HeaderComponent
  }
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
.container {
  width: 90%;
  border: 1px solid rgb(16, 36, 16);
  border-radius: 10px;
  margin: 0 auto;
}
</style>
