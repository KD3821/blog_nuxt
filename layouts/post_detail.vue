<template>
  <div>
    <Navbar />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import Navbar from "../components/Navbar";
import Footer from "../components/Footer";
export default {
  components: {Footer, Navbar},
  head() {
    return {
      link: [
        { rel: "canonical", href: `http://127.0.0.1:3000${this.$route.path}` }
      ]
    }
  }
}
</script>

<style>

</style>
