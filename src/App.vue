<template>
  <v-app>
    <v-content class="pt-10">
      <v-main>
        <Home/>
      </v-main>
    </v-content>
  </v-app>
</template>

<script>
import Home from './components/Home';

export default {
  name: 'App',

  components: {
    Home,
  },

  data: () => ({
    //
  }),
};
</script>
