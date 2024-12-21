<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>

  <div id="divHelloWorld">
    <h1>{{ msg }}</h1>
  </div>
</template>

<style scoped>
#divHelloWorld{
  padding: 2%;
  background-color: rgb(105, 0, 128);
  color: white;
  margin:2%;
}
</style>
