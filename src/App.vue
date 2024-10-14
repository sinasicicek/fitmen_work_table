<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './views/tablesant.vue'
import Navbar from './views/navbar.vue';

</script>

<template>
<div class="d-flex">
  <Navbar />
  <HelloWorld />
</div>

</template>

<style scoped>
.d-flex{display: flex;}
.d-flex-column{flex-direction: column;}
</style>

<script>
export default {

  components: { Navbar}
}
</script>