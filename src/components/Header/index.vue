<template>
        <v-card
      color="white"
      class="justify-space-between toolbar_height"
    >
    <div class="d-flex align-center justify-space-between toolbar_height p-10">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="data:image/png;base64,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"
          transition="scale-transition"
          width="120"
        />
        <div class="d-flex search_width">
            <v-autocomplete
            v-model="value"
            :items="items"
            color="primary"
            label="Search"
            dense
            filled
            background-color="#f7f7f7"
            rounded
            class="mt-5 "
          ></v-autocomplete>
          <div class="d-flex align-center icon_gap ml-5">
            <v-icon color="#1577D3" class="cursor_pointer" small>{{plusIcon}}</v-icon>
            <v-icon class="cursor_pointer" small>{{infoIcon}}</v-icon>
            <v-icon color="#FC9C36" class="ml-5 cursor_pointer" small>{{notificationIcon}}</v-icon>
          </div>
        </div>

    </div>
    </v-card>
</template>
<script>
    import { mdiBellOutline, mdiPlusCircle, mdiInformation } from '@mdi/js';
    export default {
      name: 'App',
    
      data: () => ({
        items: ['foo', 'bar', 'fizz', 'buzz'],
    value: null,
    notificationIcon: mdiBellOutline,
    plusIcon: mdiPlusCircle,
    infoIcon: mdiInformation,
      }),
    };
    </script>
<style scoped>
  .search_width {
    width: 60%;
  }
    .toolbar_height {
    height: 72px;
    padding-inline: 10px;
  }
  .icon_gap {
    gap: 20px;
  }
  .cursor_pointer {
    cursor: pointer;
  }
</style>