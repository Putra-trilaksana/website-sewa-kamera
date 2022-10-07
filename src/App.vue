<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Atas from './components/Header.vue'
import SideFilter from './components/Sidebar.vue'
import Second from './components/SecondNavbar.vue'

</script>

<template>
  <div class="container-fluid">
      <Atas />
      <Second />

      <RouterView />
</div>
</template>

<style scoped>

</style>
