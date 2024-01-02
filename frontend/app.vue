<script>
import Navbar from '../layouts/Navbar.vue'

export default {
  name: 'App',
  components: {
    Navbar,
  }
}

</script>

<template>
  <div>
    <Navbar />
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>
