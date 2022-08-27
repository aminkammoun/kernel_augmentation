<template>
  <div>
    <v-container fluid class="all-container" style="">
      <v-row
        class="pa-10 ma-auto"
        style="width: 80%"
        :color="$vuetify.theme.themes.primary"
        no-gutters
      >
        <v-col cols="12" md="4" sm="6">
          <v-card class="card-vue">
            <img src="../../assets/secure.svg" class="description-image" />
            <v-card-title
              class="
                d-flex
                justify-center
                font-weight-bold
                card-title-description
              "
              >Security</v-card-title
            >
            <v-card-text style="width: 80%" class="ma-auto text-justify"
              >Lorem ipsum dolor sit amet consectetur adipisicing elit Lorem
              ipsum dolor sit amet consectetur adipisicing elit Lorem ipsum
              dolor sit amet consectetur adipisicing elit Lorem ipsum dolor sit
              amet consectetur adipisicing elit</v-card-text
            >
          </v-card>
        </v-col>
        <v-col cols="12" md="4" sm="6">
          <v-card class="card-vue">
            <img src="../../assets/cloud.svg" class="description-image" />
            <v-card-title
              class="
                d-flex
                justify-center
                font-weight-bold
                card-title-description
              "
              >Scalability</v-card-title
            >
            <v-card-text style="width: 80%" class="ma-auto text-justify"
              >Lorem ipsum dolor sit amet consectetur adipisicing elit Lorem
              ipsum dolor sit amet consectetur adipisicing elit Lorem ipsum
              dolor sit amet consectetur adipisicing elit Lorem ipsum dolor sit
              amet consectetur adipisicing elit</v-card-text
            >
          </v-card>
        </v-col>
        <v-col cols="12" md="4" sm="6">
          <v-card class="card-vue">
            <img src="../../assets/opensource.svg" class="description-image" />
            <v-card-title
              class="
                d-flex
                justify-center
                font-weight-bold
                card-title-description
              "
              >leadership</v-card-title
            >
            <v-card-text style="width: 80%" class="ma-auto text-justify"
              >Lorem ipsum dolor sit amet consectetur adipisicing elit Lorem
              ipsum dolor sit amet consectetur adipisicing elit Lorem ipsum
              dolor sit amet consectetur adipisicing elit Lorem ipsum dolor sit
              amet consectetur adipisicing elit</v-card-text
            >
          </v-card>
        </v-col>
      </v-row></v-container
    >
  </div>
</template>

<script>
export default {}
</script>

<style></style>
