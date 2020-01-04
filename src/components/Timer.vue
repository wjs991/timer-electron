<template>
          <v-row justify="center" align="start">
             <v-col cols="2">
              <v-card>
                <v-card-title>Tileer</v-card-title>
              </v-card>

            </v-col>
            <v-col cols="2">
              <v-card>
                <v-card-title>Tileer</v-card-title>
              </v-card>

            </v-col>
          </v-row>
           
      
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