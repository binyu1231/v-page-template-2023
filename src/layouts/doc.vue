<script lang="ts" setup>
  
</script>
<template>
<div class="doc">
  <Header />
  <div class="doc-container">
    <router-view></router-view>
  </div>
</div>
</template>
<style lang="postcss">
.doc-container {
  @apply pt-24 md:pt-28 pb-8 px-6 lg:px-12 xl:pr-60;
}

.table-of-contents {
  @apply hidden xl:block w-48
    fixed right-0 bottom-0 h-[calc(100vh-5rem)] w-48 overflow-y-auto pt-32 pb-8 no-scrollbar
    border-l border-slate-200 dark:border-slate-800 text-sm
  ;
  & ol {
    @apply list-none pl-0;
  }
  & ol ol {
    @apply hidden;
  }
  & a {
    @apply 
      relative block font-normal 
      text-indigo-600 pl-4 py-1.5 
      before:absolute before:-left-px before:top-2 before:bottom-2 before:w-0.5
      decoration-none;
  }
}
</style>