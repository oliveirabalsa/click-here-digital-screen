<template>
            <v-row align-content="center pa-3" justify="space-between">
          <div>
            <v-btn small depressed color="primary">
              <v-icon> mdi-chevron-left </v-icon>
              Active Clients
            </v-btn>
          </div>
          <div>
            <v-btn small depressed color="primary"> Actions </v-btn>
            <v-btn dark small class="ml-1" depressed color="#00254B">
              Activity
            </v-btn>
          </div>
        </v-row>
</template>
<script>
export default {
  name: "ToolbarNavigator",
  data: () => ({}),
};
</script>