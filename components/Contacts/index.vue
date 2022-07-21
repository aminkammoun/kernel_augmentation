<template>
  <v-container>
    <v-card class="pa-5">
      <v-form>
        <v-row>
          <v-col cols="12" md="6"
            ><v-text-field label="email" v-model="email" outlined></v-text-field
          ></v-col>
          <v-col cols="12" md="6"
            ><v-text-field label="name" v-model="name" outlined></v-text-field
          ></v-col>
          <v-col cols="12" md="12"
            ><v-textarea v-model="description" outlined></v-textarea
          ></v-col> </v-row
      ></v-form>
      <v-card-actions>
        <v-btn block>submit</v-btn>
      </v-card-actions>
    </v-card></v-container
  >
</template>

<script>
export default {
  data: () => ({
    email: '',
    name: '',
    description: '',
  }),
}
</script>

<style></style>
