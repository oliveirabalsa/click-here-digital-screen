<template>
  <v-container class="mx-0">
    <v-row>
      <ToolbarSection />
      <MainSection />
      <TodoSection />
    </v-row>
  </v-container>
</template>

<script>
import ToolbarSection from "./Toolbar";
import MainSection from "./Main";
import TodoSection from "./Todo";


export default {
  name: "HomePage",
  data: () => ({}),
  components: { ToolbarSection, MainSection, TodoSection},
};
</script>
<style scoped>

@media (min-width: 960px) {
  .container {
    max-width: none;
  }
}
</style>
