<template>
  <div class="main">
    <Navbar />
    <MainSection />
    <Footer />
  </div>
</template>

<script setup>
import Navbar from "./components/Navbar.vue";
import MainSection from "./components/MainSection.vue";
import Footer from "./components/Footer.vue";
</script>

<script>
export default {
  components: {
    Navbar,
    MainSection,
    Footer,
  },
};
</script>

<style scoped></style>
