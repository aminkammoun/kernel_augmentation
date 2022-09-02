<template>
  <div class="nav">
    <v-card flat class="text-center error-card pa-auto" color="#191712">
      <h1
        class="h1 pa-auto"
        style="font-size: 120px"
        v-if="error.statusCode === 404"
      >
        {{ pageNotFound }}
      </h1> 
      <h1 v-else>
        {{ otherError }}
      </h1>

      <v-card-actions>
        <v-btn
          large
          class="text-capitalize mt-5 text-body-1 black--text mx-auto"
          color="#ffae33"
          to="/"
        >
          Go To Home Page
        </v-btn></v-card-actions
      >
    </v-card>
  </div>
</template>

<script>
export default {
  layout: 'empty',
  props: {
    error: {
      type: Object,
      default: null,
    },
  },
  data() {
    return {
      pageNotFound: 'Coming Soon',
      otherError: 'An error occurred',
    }
  },
  head() {
    const title =
      this.error.statusCode === 404 ? this.pageNotFound : this.otherError
    return {
      title,
    }
  },
}
</script>

<style scoped>
h1 {
  font-size: 20px;
}
</style>
