<template>
  <AppHeader />
  <Listing />
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import Listing from './components/Listing.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    Listing
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
