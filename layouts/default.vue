<template>
  <v-app dark>
    <Navbar />
    <v-main>
      <v-container class="nav pa-0" fluid> <Nuxt /></v-container>
    </v-main>
  </v-app>
</template>

<script>
import Navbar from '~/components/navbar/index.vue'
import Footer from '~/components/footer/index.vue'
export default {
  data() {
    return {
      fixed: false,
    }
  },
  components: { Navbar, Footer },
}
</script>
