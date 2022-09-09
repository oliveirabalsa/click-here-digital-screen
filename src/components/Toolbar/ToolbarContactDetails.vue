<template>
  <div>
    <v-row class="mt-4 px-2" align-content="center" justify="space-between">
      <h4>
        <v-icon color="primary">mdi-chevron-down</v-icon>
        Contact Details
      </h4>
      <v-icon color="primary">mdi-pencil</v-icon>
    </v-row>
    <v-col class="mt-4 mb-2 ml-1">
      <v-row>
        <ContactDetailFields title="Company Name" value="Acura Of Lafayette" />
        <ContactDetailFields title="Industry" value="Automotive" />
      </v-row>
      <v-row>
        <ContactDetailFields title="Street" value="6207 Jonhston St." />
        <ContactDetailFields title="City" value="Lafayette" />
      </v-row>
      <v-row>
        <ContactDetailFields title="Zip Code" value="70503" />
        <ContactDetailFields title="State" value="LA" />
      </v-row>
      <v-row>
        <ContactDetailFields title="Group" value="Fabre Automotive Group" />
        <ContactDetailFields title="Bill To" value="Fabre Automotive Group" />
      </v-row>
      <v-row>
        <ContactDetailFields
          title="Activation Closed Date"
          value="2021-02-01"
        />
        <ContactDetailFields title="Proposed Closed Date" value="2021-02-01" />
      </v-row>
      <v-row>
        <ContactDetailFields
          title="Website URL"
          value="https://acuraoflafayette.com/"
        />
      </v-row>
      <v-row>
        <ContactDetailFields
          title="Primary Goals"
          value="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed vestibulum suscipit mi eu aliquet. Etiam eget pellentesque neque. Nulla facilisi."
        />
      </v-row>
    </v-col>
  </div>
</template>
<script>
import ContactDetailFields from "./ContactDetailFields.vue";
export default {
  name: "ToolbarContactDetails",
  components: {
    ContactDetailFields,
  },
};
</script>
