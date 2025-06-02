<script setup lang="ts">
import TheWelcome from "../components/TheWelcome.vue";
import HelloWorld from "../components/HelloWorld.vue";
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <h1 class="text-center mt-8">Hello World</h1>

    <main class="flex-1">
      <HelloWorld/> 
      <TheWelcome />
    </main>
  </div>
</template>
<style scoped>
h1 {
  color: red;
  font-size: 2rem;
}
</style>
