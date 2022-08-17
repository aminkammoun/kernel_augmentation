<template>
  <div style="height: 100%" class="surface_base">
    <div class="main_container">
      <div style="align-items: center" class="d-flex justify-center">
        <div style="flex: 0 0 50%; max-width: 700px" class="text-center">
          <h1 class="textbase--text">Kernel Augmentation</h1>
          <p class="textbase--text">
            a pioneer in robot automation industry, will offer products and
            services with better performance, quality, and reliability.
          </p>
          <v-btn
            outlined
            large
            class="text-capitalize textbase--text mt-5 text-body-1"
            >explore</v-btn
          >
          <v-btn large class="text-capitalize mt-5 text-body-1"
            >our products</v-btn
          >
        </div>
        <div class="main-image">
          <img
            src="../../assets/images/illustrattion-large-dark.png"
            alt=""
            srcset=""
            style="max-width: 100%; object-fit: contain"
          />
        </div>
      </div>
    </div>
    <Who />
    <Features />
    <Description />
    <Quote />
    <Footer />
  </div>
</template>
<script>
export default {
  mounted() {
    console.log(this.$vuetify.theme)
  },
}
</script>
