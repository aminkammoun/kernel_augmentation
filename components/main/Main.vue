<template>
  <div style="height: 100%" class="surface_base">
    <div class="main_container">
      <div
        style="height: 100%; background-color: rgba(0, 0, 0, 0.61)"
        class="d-flex justify-center"
      >
        <div style="width: 50%; margin: auto" class="text-center">
          <h1
            style="
              font-size: 64.4px;
              font-weight: 800;
              line-height: 64px;
              padding: 25px 0 25px;
              opacity: 0.8;
              letter-spacing: -1px;
              text-shadow: 1px 1px 1px rgba(0, 0, 0, 0.25);
            "
            class="textbase--text"
          >
            Kernel Augmentation
          </h1>
          <p style="margin: auto; font-size: 15px" class="textbase--text">
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
      </div>
    </div>
    <Decription />
    <Quote />
  </div>
</template>
<script>
export default {
  mounted() {
    console.log(this.$vuetify.theme)
  },
}
</script>
