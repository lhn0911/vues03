<template>
  <div style="margin: 20px">
    <a :href="url" @click="preventNavigation">google</a>
  </div>
</template>

<script setup>
const url = "http://www.google.com/";

const preventNavigation = (event) => {
  const isValidUrl = url.startsWith("https://");
  if (!isValidUrl) {
    event.preventDefault();
    alert("Đường dẫn không hợp lệ");
  }
};
</script>

<style></style>
