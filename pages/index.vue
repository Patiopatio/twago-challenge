<template>
  <div class="container">
    <Navbar />
    <Hero />
    <Features />
    <Advantages />
    <Gallery />
    <Footer />
  </div>
</template>

<script>
import Advantages from '../components/Advantages.vue'
export default {
  components: { Advantages },
}
</script>

<style lang="scss">
body {
  color: rgb(41, 57, 74);
  font-family: Arial, Helvetica, sans-serif;
}
.container {
  display: flex;
  flex-direction: column;
  margin: 0 auto;
  min-height: 100vh;
  max-width: 1024px;
  background-color: rgb(255, 219, 4);
}
</style>

// rgb(41, 57, 74)
