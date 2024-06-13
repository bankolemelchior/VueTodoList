<template>
  <div>
    <TodoHeader/>

    <!-- liste des tâches -->
    <main>
      <ul class="todo-list">
        <li>
        <div class="view">
          <input type="checkbox" name="" id="" class="toggle">
          <label for="">Tâche 1</label>
        </div>
        </li>
        <li>
        <div class="view">
          <input type="checkbox" name="" id="" class="toggle">
          <label for="">Tâche 1</label>
        </div>
        </li>
        <li>
        <div class="view">
          <input type="checkbox" name="" id="" class="toggle">
          <label for="">Tâche 2</label>
        </div>
        </li>
        <li>
        <div class="view">
          <input type="checkbox" name="" id="" class="toggle">
          <label for="">Tâche 3</label>
        </div>
        </li>
      </ul>
    </main>

    <TodoFooter/>
  </div>
</template>

<script setup lang="ts">
import TodoFooter from "../components/TodoFooter.vue";
import TodoHeader from "../components/TodoHeader.vue";
</script>

<style scoped></style>
