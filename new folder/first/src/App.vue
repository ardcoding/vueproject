<template>
  <v-app>
    <v-app-bar app clipped-left>
    <v-app-bar-nav-icon/>
      <v-icon class="mx-4" large>mdi-video</v-icon>    
      <v-toolbar-title class="align-center">
        <span class="title">KOD</span>
      </v-toolbar-title>
      <v-spacer/>
      <v-text-field class="mt-7" solo placeholder="Ara...." single-line append-icon="mdi-magnify" color="green"/>
      <v-spacer/>
      <v-btn class="ml-0" icon>
        <v-icon>mdi-apps</v-icon>
      </v-btn>
      <v-btn class="ma-2" icon>
        <v-icon>mdi-bell</v-icon>
      </v-btn>
    </v-app-bar>
    <div>test</div>
  </v-app>
</template>

<script>
export default {
  name: "App",

  data: () => ({
    //
  }),
};
</script>
