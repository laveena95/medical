<template>
  <v-app :style="{background:$vuetify.theme.themes.light.background}">
    <v-layout row>
      <v-flex md3>
        <v-app :style="{background:$vuetify.theme.themes.light.background}">
          <v-container>
            <v-flex>
              <v-card class="ma-5 text-center mt-8" shaped elevation="10">
                <v-avatar class="mt-n7" size="60" elevation="10">
                  <img src="cis.jpg" alt="">
                </v-avatar>
                <v-card-title class="layout justify-center">Laveena R</v-card-title>
                <v-card-subtitle class="layouts justify-center">25 years, Hatton</v-card-subtitle>
                <v-list class="mt-n5">
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">Blood</v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">Weight</v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">Height</v-list-item-title>
                  </v-list-item>
                  <v-list-item class="mt-n5">
                    <v-list-item-subtitle>B</v-list-item-subtitle>
                    <v-list-item-subtitle>170 cm</v-list-item-subtitle>
                    <v-list-item-subtitle>50 kg</v-list-item-subtitle>
                  </v-list-item>
                </v-list>
              </v-card>
            </v-flex>

            <v-flex>
              <v-card class="ma-5 mt-n2" shaped elevation="10">
                <v-list>
                  <v-list-item>
                    <v-list-item-avatar size="10" color="cyan darken-1"></v-list-item-avatar>
                    <v-list-item-title class="nl-n2">Kognum</v-list-item-title>
                    <v-list-item-subtitle>10 mg</v-list-item-subtitle>
                  </v-list-item>

                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">MON</v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">WED</v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">FRI</v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">SUN</v-list-item-title>
                  </v-list-item>

                  <v-list-item>
                    <v-list-item-title class="mt-n5">
                      <v-list-item-subtitle>2 times in a day before food</v-list-item-subtitle>
                    </v-list-item-title>
                  </v-list-item>
                  <v-divider></v-divider>
                </v-list>
                <v-list two-line="" subheader="">
                  <v-list-item>
                    <v-list-item-avatar size="35">
                      <img src="cis.jpg" alt="">
                    </v-list-item-avatar>
                    <v-list-item-content class="ml-n2">
                      <v-list-item-title>Dr.Paull</v-list-item-title>
                      <v-list-item-subtitle>Hatton Hospital Medical</v-list-item-subtitle>
                    </v-list-item-content>
                  </v-list-item>
                </v-list>

                <v-list two-line="" subheader="" class="mt-n5">
                  <v-list-item>
                    <v-list-item-title>Surgen</v-list-item-title>
                    <v-list-item-subtitle>Spinal Pain</v-list-item-subtitle>
                  </v-list-item>
                </v-list>

                <v-list two-line="" subheader="" class="my-n8">
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">DATE</v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">TIME</v-list-item-title>
                  </v-list-item>

                  <v-list-item class="mt-n10">
                    <v-list-item-title >3 July 2020</v-list-item-title>
                    <v-list-item-title >10 a.m</v-list-item-title>
                  </v-list-item>
                </v-list>
              </v-card>
            </v-flex>

            <v-flex>
              <v-card class="ma-5 text-center mt-11" shaped="" elevation="10">
                <v-list-item three-line>
                  <v-list-item-content>
                    <v-list-item-title class="headline mb-1">
                      <v-icon>fab fa-cc-visa</v-icon>
                    </v-list-item-title>
                    <v-list-item-subtitle>2345 4546 5412</v-list-item-subtitle>
                  </v-list-item-content>
                  <v-list-item-avatar size="60" color="cyan darken-1">
                    <v-icon color="white">fas fa-plus</v-icon>
                  </v-list-item-avatar>
                </v-list-item>
              </v-card>
            </v-flex>
          </v-container>
        </v-app>
      </v-flex>
  <v-flex md9>
    <v-app :style="{background:$vuetify.theme.themes.dark.background}" class="rounded">
      
    </v-app>
  </v-flex>
    </v-layout>
  </v-app>
</template>

<script>
const gradients = [
  ['#222'],
  ['#42b3f4'],
  ['red','orange','yellow'],
  ['purple','violet'],
  ['#00c6ff','#F0F','#FF0'],
  ['#f72047','#ffd200','#ifeaea'],
]
export default {
  data:()=>({
    with:2,
    radius:10,
    padding:8,
    lineCap:'round',
    gradient:gradients[5],
    value:[0,2,5,9,5,10,3,5,0,0,1,8,2,9,0],
    gradientDirection:'top',
    gradients,
    fill:false,
    type:'trend',
    autoLineWidth:false,
    arrayEvents:null,
    date2: new Date().toISOString().substr(0,10),
  }),
  computed:{
    theme(){
      return this.$vuetify.theme.dark ? "dark":"light";
    }
  },
  mounted (){
    this.arrayElements = [...Array(6)].map(() => {
      const day = Math.floor(Math.random() * 30)
      const d = new Date()
      d.setdate(day)
      return d.toISOString().substr(0,10)
    })
  },
  methods:{
    functionEvents (date) {
      const [,,day] = date.split('-')
      if ([12,17,28].includes(parseInt(day,10))) return true
      if ([1,19,22].includes(parseInt(day,10))) return ['red','#00f']
      return false
    },

  }
}
</script>

<style scoped>
  .rounded {
    border-top-left-radius: 50px;
    border-bottom-left-radius: 50px;
  }
</style>