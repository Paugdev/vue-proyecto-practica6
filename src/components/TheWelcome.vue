<script>
export default{
  data(){
    return{
      titulo: 'Este es el componente TheWelcome.vue'
    }
  }
}
</script>

<template>
    <div id="divTheWelcome">
        <h3 v-html="titulo"></h3>
    </div>

</template>

<style scoped>
#divTheWelcome{
  background-color: rgb(240, 50, 142);
  margin: 2%;
}
</style>
