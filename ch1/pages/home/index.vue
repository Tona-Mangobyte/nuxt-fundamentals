<template>
  <h2>{{ simple }}</h2>
</template>

<script setup lang="ts">
const simple = useState(() => 'Hello World');
console.log(simple);
</script>

