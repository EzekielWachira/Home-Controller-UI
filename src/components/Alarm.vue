<template>
  <v-container>
    <v-card color="rgb(4, 4, 41)"  height="150px" dark>
      <v-container class="time-container text-center">
        <div>
          <v-list-item-title class="headline">Alarm</v-list-item-title>
        </div>
        <div>
          <v-icon color="grey" size="50">fas fa-shield-alt</v-icon>
        </div>
        <div class="mt-2">
          <v-list-item-title>OFF</v-list-item-title>
        </div>
        <v-avatar class="myavatar" size="15" color="grey"></v-avatar>
      </v-container>
    </v-card>
  </v-container>
</template>
<style lang="scss" scoped>
.myavatar{
  position: absolute;
  right: 10px;
  bottom: 10px;
}
.v-card{
  border: 1px solid rgb(0, 100, 250) !important;
  background: rgb(4, 4, 41);
  color: rgb(0, 100, 250) !important;
}
</style>
