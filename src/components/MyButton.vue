<template>
  <div>
    <button @click="$emit('increment')">Click to increment value</button>
  </div>
</template>


<script setup>
</script>

<style>
button {
  padding: 8px;
  background: red;
  color: white;
  border-radius: 40px;
}
</style>