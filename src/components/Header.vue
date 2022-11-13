<script lang="ts" setup>
  
</script>
<template>
<div class="header">
  <div>logo</div>
  <div>
    <select>
      <option value="">Framework</option>
      <option value="">Language</option>
      <option value="">Knowledge</option>
    </select>
  </div>
  <div class="search-container">
    <Search />
  </div>
  <div class="">
    switch theme
  </div>
</div>
</template>
<style lang="postcss">
.header {
  @apply flex items-center;
}

.search-container {
  @apply flex-1;
}
</style>