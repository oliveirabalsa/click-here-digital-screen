<template>
            <v-row class="mt-2 mb-4">
          <v-btn
            v-for="(buttonName, index) of buttonNames"
            :key="index"
            color="primary"
            small
            min-width="110px"
            max-width="160px"
            class="ml-1 mt-2"
            >{{ buttonName }}</v-btn
          >
        </v-row>
</template>
<script>
export default {
  name: "ToolbarButtonSection",
  data: () => ({
    buttonNames: [
      "Budgets",
      "Insights",
      "Add Assignment",
      "Website",
      "Agreement",
      "Add Assignment",
    ],
  }),
};
</script>