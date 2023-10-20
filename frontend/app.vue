<script>
import Navbar from '../layouts/Navbar.vue'
import Footer from '../layouts/Footer.vue'

export default {
  name: 'App',
  components: {
    Navbar,
    Footer
  }
}

</script>

<template>
  <div>
    <Navbar />
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
    <Footer />
  </div>
</template>
