<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper bg-[#C4B454] border-b">
      <nav class="p-4 flex justify-between ml-2 mr-2">
        <RouterLink class="font-bold text-white text-lg hover:text-black" to="/">Home</RouterLink>
        <h1 class="font-bold text-white text-lg text-right underline underline-offset-4 decoration-2">ACCES BARMAN</h1>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<style>
body {
  overflow: hidden;
}
</style>
