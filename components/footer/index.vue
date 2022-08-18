<template>
  <v-footer class="footer-container">
    <v-container>
      <div class="d-flex justify-space-between">
        <h1>Kernel Augmentation</h1>
        <section class="section-footer d-flex justify-space-between">
          <v-icon class="footer-icon" color="#ffae33">mdi-twitter</v-icon>
          <v-icon class="footer-icon" color="#ffae33">mdi-facebook</v-icon>
          <v-icon class="footer-icon" color="#ffae33">mdi-github</v-icon>
        </section>
      </div>
      <v-divider class="mt-5"></v-divider>
      <div class="d-flex justify-space-between mt-10">
        <section style="width: 155px">
          <h1>Address</h1>
          <span class="span-footer mt-10"
            >Kernel Augmentation 89/6 31-202 somewhere in the word
          </span>
        </section>
        <section>
          <h1>Industries</h1>
          <v-btn text plain class="mt-15">
            <span class="navbar-span">Autonomous Robots</span></v-btn
          ><br />
          <v-btn text plain>
            <span class="navbar-span">Internet of Things</span></v-btn
          >
        </section>
        <section>
          <h1>Developers</h1>
        </section>
        <section>
          <h1>contact</h1>
          <div class="mt-15">
            <span class="span-footer">contact@kernaug.xyz</span><br />
            <span class="span-footer">support@kernaug.xyz</span>
          </div>
        </section>
      </div>
    </v-container></v-footer
  >
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
