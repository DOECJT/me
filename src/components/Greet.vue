<script setup lang="ts">
import { toggleDark } from '@/composables/dark'
</script>

<template>
  <div pt-40px flex flex-col items-center>
    <div
      text="60px transparent" font="bold"
      class="text-bg"
    >
      doecjt
    </div>
    <div cursor-pointer text="30px" @click="toggleDark()">
      <div i="carbon-sun dark:carbon-moon" />
    </div>
  </div>
</template>

<style scoped>
.text-bg {
  background: var(--text-bg);
  -webkit-background-clip: text;
  background-clip: text;
}
</style>
