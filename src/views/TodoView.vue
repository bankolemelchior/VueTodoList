
<template>
  
    <div>
      <todo-component></todo-component>

      <router-view></router-view>
    </div>
  </template>
  
  
  <script setup lang="ts">
  import TodoComponent from '../components/TodosComponent.vue';
  </script>
  
  <!-- scoped pour la porté du style -->
  <style scoped>
  
  </style>
  