<template>
  <div>
    <div :class="['div', isActive ? 'active' : '']">Block</div>
  </div>
</template>

<script setup>
const isActive = true;
</script>

<style>
.div {
  margin: 10px 0;
  padding: 20px;
  background-color: rgb(23, 165, 139);
  color: black;
}
.active {
  background-color: red;
  color: white;
}
</style>
