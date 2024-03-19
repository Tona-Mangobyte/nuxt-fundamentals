<template>
  <h2>{{ simple }}</h2>
</template>

<script setup lang="ts">
const simple = useState(() => 'Hello World');
const appConfig = useAppConfig()
console.log(appConfig)
//console.log(simple);
</script>

