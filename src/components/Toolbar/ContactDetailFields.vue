<template>
  <v-col class="pa-0">
    <h5 class="font-weight-thin">{{ title }}</h5>
    <p class="body-2 font-weight-bold">{{ value }}</p>
  </v-col>
</template>
<script>
export default {
    props: {
        title: String,
        value: String
    },
  name: "ContactDetailFields",
};
</script>
