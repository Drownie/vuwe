<script setup lang="ts">
  defineProps<{
    todoName: string
  }>()
</script>

<template>
  <div id="todo-component">
    <input type="checkbox" name="cc">
    {{todoName}}
  </div>
</template>

<style scoped>
 #todo-component {
   display: flex;
   flex-direction: row;
   justify-content: center;
   align-items: center;
   margin-bottom: 10px;
   width: 180px;
   height: 55px;
   background-color: royalblue;
   border-radius: 10px;
 }
</style>