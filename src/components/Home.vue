<template>
  <v-container class="">
    <v-row class="">
      <v-col cols="12">
        <h1>Bienvenue dans Niagara</h1>
        <v-select
            :items="items"
            filled
            label="Filtre"
            width="8"
            height="12"
        ></v-select>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'Home',

    data: () => ({
    }),
  }
</script>
