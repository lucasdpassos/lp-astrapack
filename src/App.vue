<template>
  <v-app>
    <v-app-bar
      app
      color="#852962"
      dark
      style="display:flex;flex-direction:row;justify-content:center;align-items:center;"
    >
     <v-btn style="margin:10px;">Como funciona?</v-btn>
     <v-btn style="margin:10px;">Quem Somos?</v-btn>
    </v-app-bar>

    <v-main>
      <router-view/>
    </v-main>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
