<template>
  <v-app>
    <v-card class="elevation-16 mx-auto" width="300">
      <v-card-title class="headline justify-center">
        <center>Book Rating</center>
      </v-card-title>
      <v-card-text>
        <div class="text-center mt-12">
          <center><h2>Plot</h2></center>
          <v-rating
            v-model="rating"
            color="yellow darken-3"
            background-color="grey darken-1"
            empty-icon="$ratingFull"
            half-increments
            hover
          ></v-rating>
        </div>
      </v-card-text>
      <v-card-text>
        <div class="text-center mt-12">
          <center><h2>Dialogue</h2></center>
          <v-rating
            v-model="rating"
            color="yellow darken-3"
            background-color="grey darken-1"
            empty-icon="$ratingFull"
            half-increments
            hover
          ></v-rating>
        </div>
      </v-card-text>
      <v-card-text>
        <div class="text-center mt-12">
          <center><h2>Writing Style</h2></center>
          <v-rating
            v-model="rating"
            color="yellow darken-3"
            background-color="grey darken-1"
            empty-icon="$ratingFull"
            half-increments
            hover
          ></v-rating>
        </div>
      </v-card-text>
      <v-card-text>
        <div class="text-center mt-12">
          <center><h2>Characters</h2></center>
          <v-rating
            v-model="rating"
            color="yellow darken-3"
            background-color="grey darken-1"
            empty-icon="$ratingFull"
            half-increments
            hover
          ></v-rating>
        </div>
      </v-card-text>
      <v-card-text>
        <div class="text-center mt-12">
          <center><h2>Overall</h2></center>
          <v-rating
            v-model="rating"
            color="yellow darken-3"
            background-color="grey darken-1"
            empty-icon="$ratingFull"
            half-increments
            hover
          ></v-rating>
        </div>
      </v-card-text>
    </v-card>
  </v-app>
</template>

<script>
export default {
  name: "App",

  components: {},

  data: () => ({
    //
  })
};
</script>
