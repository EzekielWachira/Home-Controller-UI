<template>
  <v-container>
    <v-card color="rgb(4, 4, 41)"  height="150px" dark>
       <v-container >
        <v-row no-gutters="">
          <v-col cols="3">
            <v-list-item>
              <v-list-item-content>
                <v-icon size="40" class="ml-1" color="white">fas fa-cloud-showers-heavy</v-icon>
              </v-list-item-content>
            </v-list-item>
          </v-col>
          <v-col cols="6">
            <v-list-item two-line>
              <v-list-item-content>
                <v-list-item-title class="headline">Nairobi</v-list-item-title>
                <v-list-item-subtitle>Heavy rain & thunderstorms</v-list-item-subtitle>
              </v-list-item-content>
            </v-list-item>
          </v-col>
          <v-col cols="3">
            <v-list-item>
              <v-list-item-content>
                <h2>22 &deg;C</h2>
              </v-list-item-content>
            </v-list-item>
          </v-col>
        </v-row>
        <v-row class="px-5 mt-1">
          <v-col cols="4">
            <v-layout row >
              <v-list-item-title><v-icon color="white">fas fa-wind</v-icon>&nbsp;0.59 KM/H</v-list-item-title>
            </v-layout>
          </v-col>
          <v-col cols="4">
            <v-layout row >
              <v-list-item-title><v-icon color="white">fas fa-umbrella</v-icon>&nbsp;0.59 KM/H</v-list-item-title>
            </v-layout>
          </v-col>
          <v-col cols="4">
            <v-layout row >
              <v-list-item-title><v-icon color="white">fas fa-water</v-icon>&nbsp;0.59 KM/H</v-list-item-title>
            </v-layout>
          </v-col>
        </v-row>
       </v-container>
    </v-card>
  </v-container>
</template>
<style lang="scss" scoped>
.v-card{
  border: 1px solid rgb(0, 100, 250) !important;
  background: rgb(4, 4, 41);
  color: rgb(0, 100, 250) !important;
}
</style>
