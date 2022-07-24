<template>
  <div>
    <Navbar />
    <Slider />
    <div>
      <Nuxt />
    </div>
    <Footer />
  </div>
</template>

<script>
import Navbar from "../components/Navbar";
import Slider from "../components/Slider";
import Footer from "../components/Footer";

export default {
  components: {
    Footer,
    Slider,
    Navbar,
  },
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
