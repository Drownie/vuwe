<script setup lang="ts">
  defineProps(['clickButton']);
</script>

<template>
  <button @click="$props.clickButton">CLICK</button>
</template>