<template>
 <v-app id="sandbox">
    <v-navigation-drawer
      app
      overflow
      permanent
      floating
      
      mini-variant
      color="grey lighten-3"
    />

    <v-app-bar
      app
      color="grey darken-2"
    >
      <v-toolbar-title>Vuetify</v-toolbar-title>
    </v-app-bar>

    <v-content>
      
      <HelloWorld/>
    </v-content>

    <v-footer
      app
    >
      <span class="px-4">&copy; {{ new Date().getFullYear() }}</span>
    </v-footer>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';
export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
      drawers: ['Default (no property)', 'Permanent', 'Temporary'],
      primaryDrawer: {
        model: null,
        type: 'default (no property)',
        clipped: false,
        floating: false,
        mini: false,
      },
      footer: {
        inset: false,
      },
    }),
};
</script>
