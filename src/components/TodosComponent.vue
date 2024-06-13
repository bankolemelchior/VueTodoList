<template>
  <div>
    <TodoHeader/>

    <!-- liste des tâches -->
    <main class="main">
      <div class="">
        <input type="checkbox" id="toggle-all-input" class="">
        <label for="toggle-all-input" class="toggle-all-label">Tout afficher</label>
      </div>

      <ul class="todo-list">
        <li v-for="todo in todos" :key="todo.id">
        <div class="view">
          <input type="checkbox" class="toggle">
          <label :for="todo.id">{{ todo.title }}</label>
        </div>
        </li>

      </ul>
    </main>

    <TodoFooter/>
  </div>
</template>

<script setup lang="ts">
import { ref } from "vue";
import TodoFooter from "../components/TodoFooter.vue";
import TodoHeader from "../components/TodoHeader.vue";
const count = 1;
const todos = ref([
  {id:'15fc4791-46cf-449b-beaf-ba7439e2fd31', title:'Ma tâche ', completed:false, started:false},
  {id:'4e8f02b7-3d21-46c9-982e-caa963a6e961', title:'Ma tâche ', completed:false, started:false},
  {id:'350e2d74-16c9-4911-8f26-f161b7deab66', title:'Ma tâche ', completed:false, started:false},
  {id:'676fb886-fdcf-4430-96f4-9aac47434a66', title:'Ma tâche ', completed:false, started:false}
]);
</script>

<style scoped></style>
