<template>
  <div style="height: 100%">
    <div class="main_container">
      <div style="height: 100%; background-color: rgba(0, 0, 0, 0.61)"></div>
    </div>
    <v-row class="pa-10">
      <v-col cols="12" md="4" sm="6">
        Lorem ipsum dolor sit amet consectetur adipisicing elit Lorem ipsum
        dolor sit amet consectetur adipisicing elit Lorem ipsum dolor sit amet
        consectetur adipisicing elit Lorem ipsum dolor sit amet consectetur
        adipisicing elit
      </v-col>
      <v-col cols="12" md="4" sm="6">
        Lorem ipsum dolor sit amet consectetur adipisicing elit Lorem ipsum
        dolor sit amet consectetur adipisicing elit Lorem ipsum dolor sit amet
        consectetur adipisicing elit Lorem ipsum dolor sit amet consectetur
        adipisicing elit
      </v-col>
      <v-col cols="12" md="4" sm="6">
        Lorem ipsum dolor sit amet consectetur adipisicing elit Lorem ipsum
        dolor sit amet consectetur adipisicing elit Lorem ipsum dolor sit amet
        consectetur adipisicing elit Lorem ipsum dolor sit amet consectetur
        adipisicing elit
      </v-col>
    </v-row>
  </div>
</template>
<script>
export default {
  mounted() {
    console.log(this.$vuetify.theme)
  },
}
</script>
