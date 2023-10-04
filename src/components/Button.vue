<template>
  <button :style="{background: color }">{{ text }}</button>
</template>

<script>
export default {
  name: 'ButtonComponent',
  props: {
    text: {
      type: String
    },
    color: {
      type: String
    }

  }
}
</script>

<style>
  button {
    border: none;
    outline: none;
    color: white;
    padding: 0;
    width: fit-content;
    height: fit-content;
    align-self: center;
    padding: 7px;
    font-size: smaller;
  }
  button:hover{
    cursor: pointer;
    background:rgb(41, 39, 39) !important;
  }
</style>