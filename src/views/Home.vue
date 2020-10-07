<template>
  <v-app :style="{background: $vuetify.theme.themes.light.background}">
    <v-layout row>
      <v-flex m3>
        <v-app :style="{background: $vuetify.theme.themes.light.background}">
          <v-container>
            <v-flex>
              <v-card class="ma-5 text-center mt-8" shaped elevation="10">
                <v-avatar class="mt-n7" size="60" elevation="10">
                  <img src="../assets/images/a1.png" alt="Pacient">
                </v-avatar>
                <v-card-title class="layout justify-center">
                  Id Avila
                </v-card-title>
                <v-card-subtitle class="layout justify-center">
                  23 years, Mexico
                </v-card-subtitle>
                <v-list class="mt-n5">
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Blood
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Height
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Weight
                    </v-list-item-title>
                  </v-list-item>
                  <v-list-item class="mt-n5">
                    <v-list-item-subtitle>
                      +O
                    </v-list-item-subtitle>
                    <v-list-item-subtitle>
                      154 cm
                    </v-list-item-subtitle>
                    <v-list-item-subtitle>
                      70 kg
                    </v-list-item-subtitle>
                  </v-list-item>
                </v-list>
              </v-card>
            </v-flex>

            <v-flex>
              <v-card class="ma-5 mt-n2" shaped elevation="10">
                <v-list>
                  <v-list-item>
                    <v-list-item-avatar size="10" color="cyan darken-1">
                    </v-list-item-avatar>
                    <v-list-item-title class="ml-n2">
                      Paracetamol
                    </v-list-item-title>
                    <v-list-item-subtitle>
                      10 mg
                    </v-list-item-subtitle>
                  </v-list-item>
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Mon
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Wed
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Fri
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Sun
                    </v-list-item-title>
                  </v-list-item>
                  <v-list-item class="mt-n5">
                    <v-list-item-subtitle>
                      2 times at day
                    </v-list-item-subtitle>
                  </v-list-item>
                  <v-divider>
                  </v-divider>
                </v-list>
                <v-list two-line="" subheader="">
                  <v-list-item>
                    <v-list-item-avatar size="35">
                      <img src="../assets/images/a2.png" alt="Doctor">
                    </v-list-item-avatar>
                    <v-list-item-content class="ml-n2">
                      <v-list-item-title>
                        Dr. Man
                      </v-list-item-title>
                      <v-list-item-title>
                        Regional Mexican Hospital
                      </v-list-item-title>
                    </v-list-item-content>
                  </v-list-item>
                </v-list>
                <v-list two-line="" subheader="" class="mt-n5">
                  <v-list-item>
                    <v-list-item-title>
                      General Med
                    </v-list-item-title>
                    <v-list-item-subtitle>
                      Flu~
                    </v-list-item-subtitle>
                  </v-list-item>
                </v-list>
                <v-list two-line="" subheader="" class="my-n8">
                  <v-list-item>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Date
                    </v-list-item-title>
                    <v-list-item-title class="cyan--text text--darken-1">
                      Time
                    </v-list-item-title>
                  </v-list-item>
                  <v-list-item class="mt-n10">
                    <v-list-item-subtitle class="cyan--text text--darken-1">
                      Sep 30th, 2020
                    </v-list-item-subtitle>
                    <v-list-item-subtitle class="cyan--text text--darken-1">
                      10:00
                    </v-list-item-subtitle>
                  </v-list-item>
                </v-list>
              </v-card>
            </v-flex>
            <br>
            <v-flex>
              <v-card class="ma-5 text-center mt-6" shaped elevation="10">
                <v-list-item three-line="">
                  <v-list-item-content>
                    <v-list-item-title class="headline mb-1">
                      <v-icon>
                        credit_card
                      </v-icon>
                    </v-list-item-title>
                    <v-list-item-subtitle>
                      1234 5678 9012 3456
                    </v-list-item-subtitle>
                  </v-list-item-content>
                  <v-list-item-avatar size="60" color="cyan darken-1">
                    <v-icon color="white">
                      add
                    </v-icon>
                  </v-list-item-avatar>
                </v-list-item>
              </v-card>
            </v-flex>
          </v-container>
        </v-app>
      </v-flex>
      <v-flex md9>
        <v-app :style="{background: $vuetify.theme.themes.dark.background}" class="rounded">
          <v-container>
            <v-flex>
              <v-list class="mt-5">
                <v-list-item>
                  <v-list-item-title class="cyan--text text--darken-1">
                    Examinations
                  </v-list-item-title>
                  <v-list-item-action>
                    <v-btn class="ma-2" title outlined color="cyan darken-1">
                      <v-icon left>
                        remove_red_eyes
                      </v-icon>
                      See all
                    </v-btn>
                  </v-list-item-action>
                </v-list-item>
              </v-list>
            </v-flex>
            <v-flex>
              <v-row no-gutter>
                <v-col cols="12" md="4">
                  <v-row>
                    <v-col cols="12" md="2">
                      <v-card height="80px" width="10px" color="green">
                      </v-card>
                    </v-col>
                    <v-col cols="12" md="10">
                      <v-list two-line="" subheader="" class="ml-n8">
                        <v-list-item>
                          <v-list-item-content>
                            <v-list-item-subtitle>
                              Aug 20th, 2020
                            </v-list-item-subtitle>
                            <v-list-item-title>
                              Stomach ache
                            </v-list-item-title>
                            <v-list-item-subtitle>
                              Finish tratment
                            </v-list-item-subtitle>
                          </v-list-item-content>
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
                      <v-list two-line="" subheader="" class="ml-n8">
                        <v-list-item>
                          <v-list-item-content>
                            <v-list-item-subtitle>
                              Jun 20th, 2020
                            </v-list-item-subtitle>
                            <v-list-item-title>
                              Head ache
                            </v-list-item-title>
                            <v-list-item-subtitle>
                              Finish tratment
                            </v-list-item-subtitle>
                          </v-list-item-content>
                        </v-list-item>
                      </v-list>
                    </v-col>
                  </v-row>
                </v-col>
                <v-col cols="12" md="4">
                  <v-row>
                    <v-col cols="12" md="2">
                      <v-card height="80px" width="10px" color="orange">
                      </v-card>
                    </v-col>
                    <v-col cols="12" md="10">
                      <v-list two-line="" subheader="" class="ml-n8">
                        <v-list-item>
                          <v-list-item-content>
                            <v-list-item-subtitle>                              
                              May 20th, 2020
                            </v-list-item-subtitle>
                            <v-list-item-title>
                              Arm broken
                            </v-list-item-title>
                            <v-list-item-subtitle>
                              In progress tratment
                            </v-list-item-subtitle>
                          </v-list-item-content>
                        </v-list-item>
                      </v-list>
                    </v-col>
                  </v-row>
                </v-col>
              </v-row>
            </v-flex>
          </v-container>
          <v-container>
            <v-flex class="mt-12">
              <v-row no-gutters>
                <v-col cols="12" md="8">
                  <v-flex>
                    <v-list class="mt-5">
                      <v-list-item>
                        <v-list-item-title class="cyan--text text--darken-1">
                          Health curve
                        </v-list-item-title>
                        <v-btn class="mr-1" outlined color="cyan darken-1">
                          D
                        </v-btn>
                        <v-btn class="mr-1" outlined color="cyan darken-1">
                          W
                        </v-btn>
                        <v-btn class="mr-1" outlined color="cyan darken-1">
                          M
                        </v-btn>
                        <v-btn outlined color="cyan darken-1">
                          F
                        </v-btn>
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
                      :stroke-lincap="lineCap"
                      :gradient-direction="gradientDirection"
                      :fill="fill"
                      :type="type"
                      :auto-line-width="autoLineWidth"
                      auto-draw=""
                    >
                    </v-sparkline>
                  </v-flex>
                  <v-flex class="mt-5">
                    <v-list class="ml-5">
                      <v-list-item>
                        <v-list-item-avatar color="cyan darken-1" size="20px"></v-list-item-avatar>
                        <v-list-item-title>Average</v-list-item-title>
                        <v-list-item-avatar color="cyan darken-1" size="20px"></v-list-item-avatar>
                        <v-list-item-title>My data</v-list-item-title>
                      </v-list-item>
                    </v-list>
                  </v-flex>
                </v-col>
                <v-col cols="12" md="4">
                  <v-flex class="mt-10">
                    <v-list>
                      <v-list-item>
                        <v-list-item-title class="cyan--text text--darken1">
                          Nearest Treatment & Advice
                        </v-list-item-title>
                      </v-list-item>
                    </v-list>
                  </v-flex>
                  <v-flex class="ml-10">
                    <v-row>
                      <v-date-picker
                        v-model="date2"
                        :event-color="date => date[9] % 2 ? 'red' : 'yellow'"
                        :events="functionEvents"
                        color="cyan darken-1"
                      >
                      </v-date-picker>
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
  ['red', 'orange', 'yellow'],
  ['purple', 'violet'],
  ['#00c6ff', '#F0F', '#FF0'],
  ['#f72047', '#ffd200', '#0feaea']
]
export default {
  data: () => ({
    width: 2,
    radius: 10,
    padding: 8,
    lineCap: 'round',
    gradient: gradients[5],
    value: [0,2,5,9,5,10,3,5,0,0,1,8,2,9,0],
    gradientDirection: 'top',
    gradients,
    fill: false,
    type: 'trend',
    autoLineWitdh: false,
    arrayEvents: null,
    date2: new Date().toISOString().substr(0,10),
  }),
  computed: {
    theme(){
      return this.$vuetify.theme.dark ? "dark" :"light";
    }
  },
  mounted (){
    this.arrayEvents = [...Array(6)].map(() => {
      const day = Math.floor(Math.random() * 30)
      const d = new Date()
      d.setDate(day)
      return d.toISOString().substr(0,10)
    })
  },
  methods: {
    functionEvents (date) {
      const [,, day] = date.split('-')
      if([12,17,28].includes(parseInt(day, 10))) return true
      if([1,19,22].includes(parseInt(day, 10))) return ['red', '#00f']
    },
  }
}
</script>

<style scoped>
.rounded{
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
}
</style>