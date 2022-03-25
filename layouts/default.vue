<template>
  <v-app>
    <header>
      <app-bar></app-bar>
    </header>
    <nuxt />
  </v-app>
</template>

<script>
import AppBar from '../components/AppBar.vue'
export default {
  components: { AppBar },
  name: 'DEFAULT'
}
</script>

<style>

</style>
