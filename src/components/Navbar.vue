<template>
  <nav class="main-nav">

  </nav>
</template>

<script setup lang="ts">
  import { ref } from 'vue';
  import type { Component, Ref } from 'vue';
  import App from "@/App.vue";

  interface IRoute {
    path: string,
    name: string,
    component: Component
  }


  let routes: Ref<IRoute[]> = ref([
    {
      path: '/',
      name: 'Home',
      component: App
    }, {
      path: '/test',
      name: 'Test',
      component: App
    }
  ]);
  
</script>