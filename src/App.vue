<template>
  <div id="app">
    <Todos />
  </div>
</template>

<script>
import Todos from './components/Todos.vue'

export default {
  name: 'App',
  components: {
    Todos
  }
}
</script>

<style>
#app {
  font-family: Helvetica, Arial, sans-serif;
  margin-top: 60px;
}
</style>
