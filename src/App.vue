<template>
  <v-app>
    <Header></Header>
    <v-main>
      <Page/>
    </v-main>
  </v-app>
</template>

<script>
import Page from './components/MainPage';
import Header from './components/Header';


export default {
  name: 'App',

  components: {
    Page,
    Header,
},

  data: () => ({

  }),
};
</script>

