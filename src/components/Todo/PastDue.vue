<template>
    <section class="mb-4">
          <v-row class="mb-4 mt-5">
            <v-icon color="primary">mdi-chevron-down</v-icon>
            <h3 class="red--text">Past Due!</h3>
          </v-row>
          <div>
            <v-row class="mt-2" align="center" justify="space-between">
              <div>
                <v-icon color="primary" class="icon_bg"> mdi-email </v-icon>
                <span class="ml-3 font-weight-bold primary--text">Subj: </span
                ><span class="blue-grey--text font-weight-bold">
                  Discuss 2022 Budget</span
                >
              </div>
              <h4 class="blue-grey--text font-weight-light">DEC 12</h4>
            </v-row>
            <v-row class="ml-11 mt-0 blue-grey--text">
              <h5>Heather Cavanaugh Gabrielle Cerise</h5>
            </v-row>
            <v-row class="ml-11 blue-grey--text font-weight-normal">
              <p>Competitor Analysis sent</p>
            </v-row>
            <v-row align="center" justify="space-between">
              <div>
                <v-icon color="primary" class="icon_bg"> mdi-phone-in-talk </v-icon>
                <span class="ml-3 font-weight-bold primary--text">Missed Call to: </span
                ><span class="blue-grey--text font-weight-bold">
                  Jake Smith</span
                >
              </div>
              <h4 class="blue-grey--text font-weight-light">DEC 12</h4>
            </v-row>
            <v-row class="ml-11 mt-0 blue-grey--text">
              <h5>Heather Cavanaugh Gabrielle Cerise</h5>
            </v-row>
            <v-row class="ml-11 blue-grey--text font-weight-normal">
              <p>Competitor Analysis sent</p>
            </v-row>
            <v-row align="center" justify="space-between">
              <div>
                <v-icon color="primary" class="icon_bg"> mdi-calendar </v-icon>
                <span class="ml-3 font-weight-bold primary--text">Facebook Campaign Setup </span
                >
              </div>
              <h4 class="blue-grey--text font-weight-light">DEC 12</h4>
            </v-row>
            <v-row class="ml-11 mt-0 blue-grey--text">
              <h5>Heather Cavanaugh Gabrielle Cerise</h5>
            </v-row>
            <v-row class="ml-11  blue-grey--text font-weight-normal">
              <p>Competitor Analysis sent</p>
            </v-row>
          </div>
        </section>
</template>
<script>
export default {
  name: "TodoSection",
  data: () => ({}),
};
</script>
<style scoped>

.icon_bg {
  background-color: #eaf0f6;
  border-radius: 50%;
  padding: 10px;
  color: #fff;
}
</style>