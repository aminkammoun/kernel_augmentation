<template>
  <v-footer app>
    <span>&copy; {{ new Date().getFullYear() }}</span>
  </v-footer>
</template>

<script>
export default {
  data: () => ({
    fixed: false,
  }),
}
</script>

<style></style>
