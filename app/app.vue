<script setup>
useHead({
  htmlAttrs: {
    lang: 'en',
  },
})
</script>

<template>
  <UApp>
    <NuxtPage />
    <p class="py-6 pb-10 text-sm flex items-center justify-center gap-2 flex-wrap px-4">
      <UButton
        to="https://github.com/atinux/my-pull-requests"
        target="_blank"
        rel="noopener"
        color="neutral"
        variant="outlined"
        size="sm"
      >
        Create your own contribution page
      </UButton>
    </p>
    <ScrollToTop />
  </UApp>
</template>

<style lang="postcss">
body {
  @apply min-h-screen bg-white dark:bg-neutral-900 text-neutral-700 dark:text-neutral-200 font-sans;
}
</style>
