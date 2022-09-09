<template>
          <v-col class="tollbar pa-5" cols="3">
        <v-row class="mb-4">
          <v-icon color="primary">mdi-chevron-double-right</v-icon>
          <h2 class="todos">To Do´s</h2>
        </v-row>
        <v-divider></v-divider>
        <PastDue />
        <v-divider></v-divider>
        <Upcoming />
      </v-col>
</template>

<script>
import PastDue from "./PastDue.vue";
import Upcoming from "./Upcoming.vue";
    export default {
    name: "TodoSection",
    data: () => ({}),
    components: { PastDue, Upcoming }
};
</script>