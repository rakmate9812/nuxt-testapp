<template>
  <div>This is my header and the path is: {{ route.path }}</div>
</template>

<script setup lang="ts">
const route = useRoute();
</script>
