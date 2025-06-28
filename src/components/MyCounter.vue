<template>
    <div>
  <MyButton @increment="counter++" />
  <div>{{ counter }}</div>
  </div>
</template>

<script setup>
import { ref } from 'vue'
import MyButton from './MyButton.vue';

const counter = ref(0);
</script>

<style scoped>
div {
    padding: 12px;
    font-weight: 600;
    font-size: xx-large;
}
</style>