<template>
  <v-app>
    
    <v-navigation-drawer
      permanent
      fixed
      floating
      dark
      overflow
      clipped
      app
    >
      <template >
        <v-list>
          <v-list-item>
            <v-list-item-avatar>
              <v-img src="https://randomuser.me/api/portraits/women/85.jpg"></v-img>
            </v-list-item-avatar>
          </v-list-item>

          <v-list-item
            link
            two-line
          >
            <v-list-item-content>
              <v-list-item-title class="title">Cosmos Studio</v-list-item-title>
              <v-list-item-subtitle>wjstmddnjs991@gmail.com</v-list-item-subtitle>
            </v-list-item-content>
            <v-list-item-action>
              <v-icon>mdi-menu-down</v-icon>
            </v-list-item-action>
          </v-list-item>
        </v-list>
      </template>

      <v-divider></v-divider>

      <v-list
        nav
        dense
      >
        <v-list-item link>
          <v-list-item-icon>
            <v-icon>mdi-folder</v-icon>
          </v-list-item-icon>
          <v-list-item-title>My Project</v-list-item-title>
        </v-list-item>
        
        <v-list-item link>
          <v-list-item-icon>
            <v-icon>mdi-star</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Starred</v-list-item-title>
        </v-list-item>

        <v-list-item link>
        <v-list-item-icon>
            <v-icon>mdi-timer</v-icon>
          </v-list-item-icon>
          <v-list-item-title>Timer</v-list-item-title>
      </v-list-item>
      </v-list>

      
    </v-navigation-drawer>
  
    <v-content>
      <HelloWorld/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data () {
      return {
        items: [
          { title: 'Home', icon: 'dashboard' },
          { title: 'About', icon: 'question_answer' },
        ],
        links: ['Home', 'Contacts', 'Settings'],
        mini: true,
      }
    },
};
</script>
