<template>

<v-layout>
  <v-row justify="center" align="start">
            <v-col cols="12">
              <v-layout >
                <v-toolbar flat color="grey lighten-5">
                  <v-icon>mdi-anchor
                </v-icon>
                <v-toolbar-title>dd</v-toolbar-title>

                </v-toolbar>
                
              </v-layout>
                
            </v-col>
 
             <v-col cols="6">
              <v-card>
                <v-card-title>Tileer</v-card-title>
                 <v-card-text>
                  <div>Word of the Day</div>
                  <p class="display-1 text--primary">
                    be•nev•o•lent
                  </p>
                  <p>adjective</p>
                  <div class="text--primary">
                    well meaning and kindly.<br>
                    "a benevolent smile"
                  </div>
                </v-card-text>
              </v-card>

            </v-col>
            <v-col cols="5">
              <v-card>
                <v-card-title>Tileer</v-card-title>
              </v-card>
            </v-col>
            <v-col cols="10">
              <v-card>
                <v-card-title>Tileer</v-card-title>
              </v-card>

            </v-col>
          </v-row>
          

</v-layout>

           
      
</template>

<script>
export default {
    name: 'Timer',
   data () {
      return {
        alignmentsAvailable: [
          'start',
          'center',
          'end',
          'baseline',
          'stretch',
        ],
        alignment: 'center',
        dense: false,
        justifyAvailable: [
          'start',
          'center',
          'end',
          'space-around',
          'space-between',
        ],
        justify: 'center',
      }
    },
}
</script>