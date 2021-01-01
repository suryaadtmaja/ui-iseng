<template>
  <div class="w-full h-full">
    <Navbar />
    <Hero />
  </div>
</template>

<script>
import Navbar from "./components/Navbar.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    Navbar,
    Hero,
  },
};
</script>
