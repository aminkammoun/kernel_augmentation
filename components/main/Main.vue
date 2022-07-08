<template>
  <v-card class="logo d-flex justify-center" dense flat>
    <img
      src="../../assets/kernel_augmentation.jpg"
      alt=""
      srcset=""
      style="max-width: 100%"
    />
  </v-card>
</template>
<script>
export default {
  mounted() {
    console.log(this.$vuetify.theme)
  },
}
</script>
