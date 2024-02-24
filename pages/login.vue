import { definePageMeta } from "#imports";

<template>
  <div>
    <Login />
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