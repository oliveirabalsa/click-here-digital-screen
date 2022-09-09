<template>
    <v-card class="mt-10 pa-5">
          <v-row class="pa-5 mb-4" justify="space-between">
            <v-row class="mt-1" align="center">
              <v-icon color="#efbb50" class="icon_bg">mdi-star</v-icon>
              <h4 class="ml-4 blue-grey--text lighten-5">
                Create Watchlist Notes
              </h4>
            </v-row>
            <v-row class="mt-0" align="center" justify="end">
              <div
                v-for="(item, index) of new Array(2)"
                :key="index"
                class="img_bg "
              ></div>
              <v-icon class="ml-3">mdi-dots-horizontal</v-icon>
            </v-row>
          </v-row>
          <v-divider></v-divider>
          <v-row class="mt-3" justify="center">
            <VueEditor class="mt-2" placeholder="Main reason for priority" />
            <VueEditor class="mt-2 " placeholder="What are we doing this week to provide value?" />
            <VueEditor class="mt-2 mb-10" placeholder="How to remove?" />
          </v-row>
          <v-row class="my
          -10" justify="end">
            <v-btn color="primary">Save Watchlist Notes <v-icon>mdi-star</v-icon></v-btn>
          </v-row>
        </v-card>
</template>
<script>
import { VueEditor } from "vue2-editor";

export default {
  components: {
    VueEditor,
  },
  name: "MainWatchlistNotes",
  data: () => ({}),
};
</script>