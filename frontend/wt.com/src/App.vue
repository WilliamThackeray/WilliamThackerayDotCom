<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <v-app>
    <v-app-bar>
      <v-app-bar-title class="title">WilliamThackeray.com</v-app-bar-title>
      <v-tabs>
        <v-tab>Home</v-tab>
        <v-tab>About</v-tab>
        <v-tab>Projects</v-tab>
      </v-tabs>
    </v-app-bar>

    <v-main> Main </v-main>

    <v-footer>Footer</v-footer>
  </v-app>

  <RouterView />
</template>

<style scoped>
.title {
  font-family: monospace;
  font-family: var(--primary-title-font);
}
</style>
