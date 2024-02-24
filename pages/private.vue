<template>
  <div>
    <h1> This is private page. Only authenticated users can view this.</h1>
  </div>
</template>

<script lang="ts" setup>
definePageMeta({ middleware: 'auth' })
</script>

<style>

</style>