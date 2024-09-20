<template>
  <div>
    <h1 :elementId="heading">Heading</h1>
  </div>
</template>

<script setup>
const heading = "heading";
</script>

<style>
#heading {
  color: blue;
}
</style>
