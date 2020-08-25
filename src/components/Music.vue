<template>
  <v-container>
    <v-card color="rgb(4, 4, 41)"  height="150px" dark>
      <v-container class="text-center">
        <v-row>
          <v-col cols="2">
            <v-icon color="white" class="ml-3">fas fa-music</v-icon>
          </v-col>
          <v-col cols="10">
            <v-list-item-title class="mr-3">Imagine Dragon</v-list-item-title>
          </v-col>
        </v-row>
        <div>
          <v-list-item-subtitle>Whatever it takes</v-list-item-subtitle>
        </div>
        <v-row>
          <v-col cols="3">
            <v-icon color="white" size="20">fas fa-pause</v-icon>
          </v-col>
          <v-col cols="3">
            <v-icon color="white" size="20">fas fa-play</v-icon>
          </v-col>
          <v-col cols="3">
            <v-icon color="white" size="20">fas fa-play</v-icon>
          </v-col>
          <v-col cols="3">
            <v-icon color="white" size="20">fas fa-share</v-icon>
          </v-col>
        </v-row>
      </v-container>
    </v-card>
  </v-container>
</template>
<style lang="scss" scoped>
p i{
  color: white;
}
.v-card{
  border: 1px solid rgb(0, 100, 250) !important;
  background: rgb(4, 4, 41);
  color: rgb(0, 100, 250) !important;
}
</style>
