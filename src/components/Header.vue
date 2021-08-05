<template>
  <header class="header">
    <TopBar/>
  </header>
</template>

<script>
import TopBar from './TopBar.vue'

export default {
  name: 'Header',
  components: {
    TopBar
  }
}
</script>

<style>
.header {
  margin: 0;
  padding: 0;
  
}
</style>
