<script setup>
import { RouterLink, RouterView } from 'vue-router'
import Navbar from './components/Navbar.vue'
</script>

<template>
  <header>
    <h1 class="site-heading text-center text-faded d-none d-lg-block">
      <span class="site-heading-lower">NAYCO CORP</span>
      <span class="site-heading-upper text-primary mb-3">Archivos</span>
    </h1>
  </header>
  <Navbar />

  <RouterView />

  <footer class="footer text-faded text-center py-5">
    <div class="container"><p class="m-0 small">Copyright &copy; NAYCO CORP 2022</p></div>
  </footer>
</template>
