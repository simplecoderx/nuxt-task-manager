<template>
  <div>
    <h1>This is guest view.</h1>
  </div>
</template>

<script setup lang="ts">
definePageMeta({
  auth: {
    unauthenticatedOnly: true,
    navigateAuthenticatedTo: '/private',
  },
})
</script>

<style>

</style>