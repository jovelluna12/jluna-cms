<template>
  <div class="about">
    <h1>This is the about page</h1>
  </div>

  <TheWelcome />

</template>

<script setup>
import TheWelcome from '../components/TheWelcome.vue'
</script>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 10vh;
    display: flex;
    align-items: center;
  }
}
</style>
