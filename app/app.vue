<template>
  <div>
    <NuxtRouteAnnouncer />
    <NuxtPage />
  </div>
</template>

<script setup>
if (process.env.NODE_ENV === 'production') {
  await navigateTo('https://github.com/voltcrash', { external: true })
}
</script>
