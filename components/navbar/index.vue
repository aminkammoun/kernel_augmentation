<template>
  <div>
    <v-app-bar elevate-on-scroll fixed app class="nav px-10">
      <v-toolbar-title
        v-text="title"
        to="/"
        style="font-size: 35px; font-weight: 950"
      />
      <v-spacer />
      <v-btn text plain to="/aboutus">
        <span class="navbar-span">about us</span>
      </v-btn>
      <v-btn text plain to="/contact">
        <span class="navbar-span">contact us</span>
      </v-btn>
      <!-- <v-btn icon @click="switchTheme">
        <v-icon v-if="!this.$vuetify.theme.isDark"
          >mdi-moon-waning-crescent</v-icon
        >
        <v-icon v-else>mdi-weather-sunny</v-icon>
      </v-btn> -->
    </v-app-bar>
  </div>
</template>

<script>
export default {
  data: () => ({
    clipped: false,
    drawer: false,
    fixed: false,
    items: [
      {
        icon: 'mdi-apps',
        title: 'Welcome',
        to: '/',
      },
      {
        icon: 'mdi-chart-bubble',
        title: 'Inspire',
        to: '/inspire',
      },
    ],
    miniVariant: false,
    right: true,
    rightDrawer: false,
    title: 'Kernel Augmentation',
  }),
  computed: {
    theme() {
      this.$vuetify.theme.dark
        ? localStorage.setItem('theme', 'dark')
        : localStorage.setItem('theme', 'light')
      localStorage.setItem('theme', this.$vuetify.theme.dark)
      return this.$vuetify.theme.dark ? 'dark' : 'light'
    },
  },
  methods: {
    switchTheme() {
      this.$vuetify.theme.isDark = !this.$vuetify.theme.isDark
    },
  },
}
</script>

<style></style>
