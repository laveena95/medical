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
  <v-flex md9 >
    <v-app :style="{background:$vuetify.theme.themes.dark.background}" class="rounded">
      <v-container>
        <v-flex>
          <v-list class="mt-5">
            <v-list-item>
              <v-list-item-tile class="cyan--text text--darken--1">Examination</v-list-item-tile>
              <v-list-item-action>
                <v-btn class="ma-2" tile outlined="" color="cyan darken-1">
                  <v-icon left="">fas fa-eye</v-icon>SEE ALL
                </v-btn>
              </v-list-item-action>
            </v-list-item>
          </v-list>
        </v-flex>
  <v-flex>
    <v-row no-gutters="">
      <v-col cols="12" md="4">
        <v-row>
          <v-col cols="12" md="2">
            <v-card height="80px" width="10px" color="green">
            </v-card>
          </v-col>
          <v-col cols="12" md="10">
            <v-list two-line="" subheader="" class="nl-n8">
              <v-list-item>
                <v-list-item-con>
                  <v-list-item-subtitle>4 July 2020</v-list-item-subtitle>
                  <v-list-item-title>Heart Disease</v-list-item-title>
                  <v-list-item-subtitle>On going treatement</v-list-item-subtitle>
                </v-list-item-con>
              </v-list-item>
            </v-list>
          </v-col>
        </v-row>
      </v-col>

      <v-col cols="12" md="4">
        <v-row>
          <v-col cols="12" md="2">
            <v-card height="80px" width="10px" color="red">
            </v-card>
          </v-col>
          <v-col cols="12" md="10">
            <v-list two-line="" subheader="" class="nl-n8">
              <v-list-item>
                <v-list-item-con>
                  <v-list-item-subtitle>5 July 2020</v-list-item-subtitle>
                  <v-list-item-title>Odteoporosis</v-list-item-title>
                  <v-list-item-subtitle>Incurable</v-list-item-subtitle>
                </v-list-item-con>
              </v-list-item>
            </v-list>
          </v-col>
        </v-row>
      </v-col>

      <v-col cols="12" md="4">
        <v-row>
          <v-col cols="12" md="2">
            <v-card height="80px" width="10px" color="yellow">
            </v-card>
          </v-col>
          <v-col cols="12" md="10">
            <v-list two-line="" subheader="" class="nl-n8">
              <v-list-item>
                <v-list-item-con>
                  <v-list-item-subtitle>5 July 2020</v-list-item-subtitle>
                  <v-list-item-title>Blood Pressure</v-list-item-title>
                  <v-list-item-subtitle>Examinations</v-list-item-subtitle>
                </v-list-item-con>
              </v-list-item>
            </v-list>
          </v-col>
        </v-row>
      </v-col>
    </v-row>
  </v-flex>
  <v-flex class="mt-12">
    <v-row no-gutters="">
      <v-col cols="12" md="8">
        <v-flex>
          <v-list class="mt-5">
            <v-list-item>
              <v-list-item-title class="cyan--text text--darken-1">Health Curve</v-list-item-title>
              <v-item-content>
                <v-btn class="mr-1" outlined color="cyan darken-1">D</v-btn>
              </v-item-content>
              <v-item-content>
                <v-btn class="mr-1" outlined color="cyan darken-1">W</v-btn>
              </v-item-content>
              <v-item-content>
                <v-btn class="mr-1" outlined color="cyan darken-1">M</v-btn>
              </v-item-content>
              <v-item-content>
                <v-btn outlined color="cyan darken-1">Y</v-btn>
              </v-item-content>
            </v-list-item>
          </v-list>
        </v-flex>
        
        <v-flex>
          <v-sparkline
            :value="value"
            :gradient="gradient"
            :smooth="radius || false"
            :padding="padding"
            :line-width="width"
            :stroke-lineCap="lineCap"
            :gradient-direction="gradientDirection"
            :fill="fill"
            :type="type"
            :auto-line-width="autoLineWidth"
            auto-draw=""
            >
          </v-sparkline>
        </v-flex>
        <v-flex class="mt-5">
          <v-list class="nl-5">
            <v-list-item>
              <v-list-item-avatar color="cyan darken-1" size="20px"></v-list-item-avatar>
              <v-list-item-title>Average</v-list-item-title>
              <v-list-item-avatar color="cyan darken-1" size="20px"></v-list-item-avatar>
              <v-list-item-title class="ml-5">My Data</v-list-item-title>
            </v-list-item>
          </v-list>
        </v-flex>
        </v-col>
        <v-col cols="12" md="4">
          <v-flex class="nl-10">
            <v-list>
              <v-list-item>
                <v-list-item-title class="cyan--text text--darken-1">Nearest Treatment & Advice</v-list-item-title>
              </v-list-item>
            </v-list>
          </v-flex>
          <v-flex class="nl-10">
            <v-row>
              <v-date-picker
              v-model="date2"
              :event-color="date=>date[9] % 2 ? 'red': 'yellow'"
              :events="functionEvents"
              color="cyan darken-1"
              ></v-date-picker>
            </v-row>
          </v-flex>
        </v-col>
    </v-row>
  </v-flex>
      </v-container>
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