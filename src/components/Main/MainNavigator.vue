<template>
            <v-tabs v-model="active_tab">
          <v-tab v-for="(tab, index) of tabs" :key="index">{{ tab }}</v-tab>
        </v-tabs>
</template>
<script>
export default {
  name: "MainNavigator",
  data: () => ({
    tabs: [
      "History",
      "Notes",
      "Email",
      "Calls",
      "Tasks",
      "Meetings",
      "Watchlist",
    ],
    active_tab: 6,
  }),
};
</script>