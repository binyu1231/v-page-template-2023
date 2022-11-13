<route lang="yaml">
meta:
  layout: page-not-found
</route>
<script setup lang="ts">
</script>

<template>
  <div class="page-not-found bg-indigo-500">
    <span>not found</span>
  </div>
</template>
<style lang="postcss">
.page-not-found {
  & span {
    @apply bg-red-500;
  }
}
</style>
