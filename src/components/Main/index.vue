<template>
          <v-col class="main" cols="5">
        <MainNavigator />    
        <MainWatchlistNotes />
      </v-col>
</template>
<script>
import MainNavigator from "./MainNavigator.vue";
import MainWatchlistNotes from "./MainWatchlistNotes.vue";
    export default {
    name: "MainSection",
    data: () => ({}),
    components: { MainNavigator, MainWatchlistNotes }
};
</script>
<style scoped>
.main {
  background-color: #fafafa;
  height: 95vh;
  border-top: 1px solid rgba(173, 173, 173, 0.2);
}
</style>