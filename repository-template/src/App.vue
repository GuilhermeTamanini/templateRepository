<script setup>
import Navbar from "@/components/NavbarComp.vue";
import Footer from "@/components/FooterComp.vue";
</script>
<template>
  <Navbar />
  <div class="pageContentWrapper">
    <RouterView />
  </div>
  <div class="footer bg-dark">
    <Footer />
  </div>
</template>
