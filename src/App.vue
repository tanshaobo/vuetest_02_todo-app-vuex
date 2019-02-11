<template>
  <div id="app">
    <CompletedTodos></CompletedTodos>
    <GetTodo></GetTodo>
    <CurrentTodos></CurrentTodos>
  </div>
</template>

<script>
import GetTodo from '@/components/GetTodo'
import CurrentTodos from '@/components/CurrentTodos'
import CompletedTodos from './components/CompletedTodos.vue'
export default {
  components: {
    GetTodo,
    CurrentTodos,
    CompletedTodos
  }
}
</script>

<style>
</style>
