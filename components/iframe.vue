<template>
    <div class="iframe-container">
      <iframe
        :src="src"
        width="100%"
        height="500px"
        frameborder="0"
        allowfullscreen
      ></iframe>
    </div>
  </template>
  
  <script setup>
  defineProps({
    src: {
      type: String,
      required: true
    }
  });
  </script>
  
  <style scoped>
  .iframe-container {
    width: 100%;
    height: 100%;
  }
  </style>  