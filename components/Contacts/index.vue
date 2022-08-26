<template>
  <v-container fluid class="main_container">
    <v-row>
      <v-col cols="12" md="6" lg="6"
        ><v-card
          class="pa-5 description-section"
          flat
          style="width: 50%; margin: auto"
        >
          <v-form>
            <v-row>
              <v-col cols="12" md="6"
                ><v-text-field
                  label="email"
                  v-model="email"
                  outlined
                ></v-text-field
              ></v-col>
              <v-col cols="12" md="6"
                ><v-text-field
                  label="name"
                  v-model="name"
                  outlined
                ></v-text-field
              ></v-col>
              <v-col cols="12" md="12"
                ><v-text-field
                  label="topic"
                  v-model="topic"
                  outlined
                ></v-text-field
              ></v-col>
              <v-col cols="12" md="12"
                ><v-textarea
                  label="description"
                  v-model="description"
                  outlined
                ></v-textarea
              ></v-col> </v-row
          ></v-form>
          <v-card-actions>
            <v-btn block @click="submit" class="btns">submit</v-btn>
          </v-card-actions>
        </v-card></v-col
      >
      <v-col cols="12" md="6" lg="6" class="pa-15">
        <span class="pa-15">
          <h2 style="width: 40%% !important">
            Tell us what you consider connecting with Kernel Augmentation
          </h2></span
        >
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    email: '',
    name: '',
    topic: '',
    description: '',
  }),
  methods: {
    submit() {
      console.log(this.name, this.email, this.description)
    },
  },
}
</script>

<style></style>
