<script setup lang="ts">
const { params } = useRoute();
</script>

<template>
  <div>
    <p>userid:{{ params.id }}</p>
    <div>
      <NuxtLink href="/">to home</NuxtLink>
    </div>
  </div>
</template>
