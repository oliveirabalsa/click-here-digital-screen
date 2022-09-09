<template>
    <div>
     <v-row
          class="mt-5 mb-3 px-2"
          align-content="center"
          justify="space-between"
        >
          <h4>
            <v-icon color="primary">mdi-chevron-down</v-icon>
            Team
          </h4>
        </v-row>
        <v-row class="mb-5 ml-2">
          <div
            v-for="(item, index) of new Array(5)"
            :key="index"
            class="img_bg mr-1"
          ></div>
        </v-row>
    </div>
</template>
<script>
export default {
  name: "ToolbarTeamSection",
  data: () => ({}),
};
</script>
<style>
    .img_bg {
  background-color: #efbb50;
  border-radius: 50%;
  padding: 20px;
  color: #fff;
}
</style>