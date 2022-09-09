<template>
  <v-col class="tollbar" cols="4">
    <ToolbarNavigator />
    <ToolbarActions />
    <v-divider></v-divider>
    <ToolbarContactDetails />
    <v-divider></v-divider>
    <ToolbarAgreement />
    <v-divider></v-divider>
    <ToolbarButtonSection />
    <v-divider></v-divider>
    <ToolbarTeamSection />
  </v-col>
</template>
<script>
import ToolbarContactDetails from "./ToolbarContactDetails";
import ToolbarNavigator from "./ToolbarNavigator";
import ToolbarActions from "./ToolbarActions";
import ToolbarAgreement from "./ToolbarAgreement";
import ToolbarButtonSection from "./ToolbarButtonSection";
import ToolbarTeamSection from "./ToolbarTeamSection";
export default {
  name: "ToolbarPage",
  data: () => ({}),
  components: {
    ToolbarContactDetails,
    ToolbarNavigator,
    ToolbarActions,
    ToolbarAgreement,
    ToolbarButtonSection,
    ToolbarTeamSection,
  },
};
</script>
<style scoped>
.tollbar {
  background-color: #fff;
  border-style: solid;
  border-width: 1px;
  border-color: rgba(173, 173, 173, 0.2);
}
</style>
