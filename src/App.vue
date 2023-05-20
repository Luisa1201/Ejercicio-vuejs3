<script setup>
import { ref } from 'vue'
const title = ref('Ejercicio')

  

</script>

<template>
  <div>
    <ul>
      <h2>{{ title }}</h2>
      <input type="text" v-model="title" />
      <button @click="addTarea">Crear tarea</button>
    </ul>
  </div>
</template>

<style scoped>
ul {
  width: 420px;
  margin: 0 auto;
  background: gainsboro;
  border-radius: 8px;
}

</style>
