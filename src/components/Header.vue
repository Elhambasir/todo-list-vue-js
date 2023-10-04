<template>
  <div class="header">
    <h3>{{ msg }}</h3>
    <ButtonComponent text="Add Task" color="black"/>
  </div>
</template>

<script>
import ButtonComponent from './Button.vue'
export default {
  name: 'HeaderComponent',
  components: {
    ButtonComponent
  },
  props: {
    msg: {
      type: String,
      default: 'Hello Elham!',
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .header {
    display: flex;
    justify-content: space-around;
  }
</style>
