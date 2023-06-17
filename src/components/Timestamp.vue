<template>
    <span class="timestamp" v-text="timestampPropNieto" />
  </template>
  
  <script setup>

  defineProps({
    timestampPropNieto: {
      
      type: String,
     
      default: "A random date",
    },
  });
  </script>