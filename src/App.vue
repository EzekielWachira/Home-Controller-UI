<template>
  <v-app>
    <v-content>
      <v-container>
        <v-layout row wrap>
          <v-flex xs8 md3>
            <Time />
          </v-flex>
          <v-flex xs4 md2>
            <meeting></meeting>
          </v-flex>
          <v-flex xs6 md2>
            <dining></dining>
          </v-flex>
          <v-flex xs6 md2>
            <back-door></back-door>
          </v-flex>
          <v-flex xs6 md3>
            <music></music>
          </v-flex>
        </v-layout>
        <v-layout row wrap>
          <v-flex xs8 md5>
            <weatherr></weatherr>
          </v-flex>
          <v-flex xs6 md2>
            <front-door></front-door>
          </v-flex>
          <v-flex xs6 md2>
            <main-lamp></main-lamp>
          </v-flex>
          <v-flex xs6 md3>
            <frigde></frigde>
          </v-flex>
        </v-layout>
         <v-layout row wrap>
          <v-flex xs8 md3>
            <kitchen></kitchen>
          </v-flex>
          <v-flex xs4 md2>
            <living></living>
          </v-flex>
          <v-flex xs6 md2>
            <bedroom></bedroom>
          </v-flex>
          <v-flex xs6 md2>
            <fan></fan>
          </v-flex>
          <v-flex xs6 md3>
            <alarm></alarm>
          </v-flex>
        </v-layout>
      </v-container>
    </v-content>
    <v-container class="mycontainer">
      <v-layout row class=" ml-10 mr-10" justify-space-around>
        <v-flex>
          <navs></navs>
        </v-flex>
      </v-layout>
    </v-container>
  </v-app>
</template>

<script>
// import Navbar from '@/components/Navbar'
// import NavbarMain from '@/components/NavbarMain'
// import Weather from '@/components/Weather'
import Navs from '@/components/Navs'
import Time from '@/components/Time'
import Meeting from '@/components/Meeting'
import Dining from '@/components/Dining'
import BackDoor from '@/components/BackDoor'
import Weatherr from '@/components/Weatherr'
import FrontDoor from '@/components/FrontDoor'
import MainLamp from '@/components/MainLamp'
import Kitchen from '@/components/Kitchen'
import Bedroom from '@/components/Bedroom'
import Living from '@/components/Living'
import Fan from '@/components/Fan'
import Alarm from '@/components/Alarm'
import Frigde from '@/components/Frigde'
import Music from '@/components/Music'

export default {
  name: 'App',

  components: {
    Navs,
    Time,
    Meeting,
    Dining,
    BackDoor,
    Weatherr,
    FrontDoor,
    MainLamp,
    Kitchen,
    Bedroom,
    Living,
    Fan,
    Alarm,
    Frigde,
    Music
  },

  data: () => ({
    //
  })
}
</script>
<style>
.v-main__wrap{
  background: rgb(4, 4, 41);
}
.container{
  background: rgb(4, 4, 41);
}
.v-application--wrap{
  background: rgb(4, 4, 41);
}
.myflex{
  width: 70px !important;
}

/* .mycontainer{
  position: absolute;
  bottom: 0;
} */

/* @media screen and (max-width: 500px){
  .mycontainer{
    right: 0;
  }
} */

</style>
