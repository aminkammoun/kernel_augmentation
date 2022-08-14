<template>
  <v-footer>
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

<style lang="scss" scoped>
.footer {
  bottom: 0;
  position: sticky;
  height: auto;
}
</style>
