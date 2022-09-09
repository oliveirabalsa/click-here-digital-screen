<template>
  <v-container class="mx-0 reset_max_width">
    <v-row>
      <ToolbarPage />
      <MainSection />
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
    </v-row>
  </v-container>
</template>

<script>
import ToolbarPage from "./Toolbar";
import MainSection from "./Main";
import PastDue from "./Todo/PastDue";
import Upcoming from "./Todo/Upcoming";

export default {
  name: "HomePage",
  data: () => ({}),
  components: { ToolbarPage, MainSection, PastDue, Upcoming },
};
</script>
<style scoped>
.tollbar {
  background-color: #fff;
  border-style: solid;
  border-width: 1px;
  border-color: rgba(173, 173, 173, 0.2);
}


@media (min-width: 960px) {
  .container {
    max-width: none;
  }
}
</style>
