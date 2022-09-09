<template>
  <v-col class="mb-7">
    <v-row>
      <h2 class="title mx-auto pt-4 pb-3 font-weight-black">
        Acura Of Lafayette
      </h2>
    </v-row>
    <v-row align-content="center" justify="center">
      <v-icon
        v-for="(icon, index) of icons"
        :key="index"
        class="mr-1 icon_bg"
        :color="index === icons.length - 1 ? '#efbb50' : 'primary'"
        >{{ icon }}</v-icon
      >
    </v-row>
  </v-col>
</template>
<script>
import {
  mdiSquareEditOutline,
  mdiEmail,
  mdiPhoneInTalk,
  mdiFormatListChecks,
  mdiCalendarMonth,
  mdiStar,
} from "@mdi/js";
export default {
  name: "ToolbarActions",
  data: () => ({
    icons: [
      mdiSquareEditOutline,
      mdiEmail,
      mdiPhoneInTalk,
      mdiFormatListChecks,
      mdiCalendarMonth,
      mdiStar,
    ],
  }),
};
</script>
<style scoped>
.icon_bg {
  background-color: #eaf0f6;
  border-radius: 50%;
  padding: 10px;
  color: #fff;
}
.title {
  color: #efbb50;
}
</style>
