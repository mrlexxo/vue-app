<script setup>
const color = 'blue';
const isAdmin = true;
</script>

<template>
  <header :class="`color-${color}`">Logo</header>
  <main :class="color">Content</main>
  <div>{{ isAdmin ? "Admin" : "Not Admin" }}</div>
  <footer>{{ 10 + 20 }}</footer>
</template>

<style scoped></style>