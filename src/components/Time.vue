<template>
  <v-container>
    <v-card color="rgb(4, 4, 41)"  height="150px">
      <v-container class="time-container text-center">
        <h3>{{ date }}</h3>
        <h1>10:30 AM</h1>
        <div class="mt-6 ml-2 text-start flex-row">
          <h4><v-icon size="15" color="white">fas fa-clock</v-icon> &nbsp; 10:30 AM</h4>
        </div>
      </v-container>
    </v-card>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    date: '',
    time: ''
  }),
  mounted () {
    this.date = new Date().toDateString()
    // this.time = Date.now()
  }
  // methods: {

}
</script>

<style lang="scss" scoped>
.v-card{
  border: 1px solid rgb(0, 100, 250) !important;
  background: rgb(4, 4, 41);
  color: rgb(0, 100, 250) !important;
}
</style>
