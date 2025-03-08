<script setup>
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <header></header>
  <main>
    <TheWelcome />
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

/* @media (min-width: 1024px) {
  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
} */

</style>
