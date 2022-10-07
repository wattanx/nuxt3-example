<script setup lang="ts">
const id = ref("1");
</script>

<template>
  <div>
    <div>
      <input v-model="id" />
    </div>
    <div>
      <NuxtLink :href="`/slug/${id}`">to slug</NuxtLink>
    </div>
    <NuxtLin to="/about">ABOUT</NuxtLin>
  </div>
</template>
