<template>
  <div>
    <div class="container">
      <Navbar />
      <MainComponent />
    </div>
    <Footer />
  </div>
</template>

<script>
import Footer from './components/Footer.vue'
import MainComponent from './components/MainComponent.vue'
import Navbar from './components/Navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    MainComponent,
    Footer,
  }
}
</script>

<style></style>
