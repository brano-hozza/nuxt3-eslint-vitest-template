<script setup lang="ts">
const appConfig = useAppConfig();
</script>
<template>
  <div>
    <NuxtWelcome />
    <h1>{{ appConfig.title }}</h1>
  </div>
</template>
