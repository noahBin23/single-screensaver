<script setup lang="ts">
import TheWelcome from '../components/TheWelcome.vue'
import '@/webcomponents/wcs-clock'
</script>

<template>
  <main>
    <wcs-clock></wcs-clock>
  </main>
</template>

<style scoped>
main {
  margin: auto;
  width: 100%;
}
</style>
