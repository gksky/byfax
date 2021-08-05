<template>
  <div class="container">
    <Header/>
  </div>
</template>

<script>
import Header from './Header.vue'

export default {
  name: 'Container',
  components: {
    Header
  }
}
</script>

<style>
.container {
  margin: 0;
  padding: 0;

}
</style>
