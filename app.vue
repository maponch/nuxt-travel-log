<script setup lang="ts">
const colorMode = useColorMode();
colorMode.preference = "system";
console.log("Mode actuel :", colorMode.value);
</script>

<template>
  <NuxtLayout>
    <NuxtPage />
  </NuxtLayout>
</template>
