<template>
  <v-app-bar fixed
      app
      color="deep-orange"
      dark
      dense
      flat
      elevate-on-scroll
    >
    <v-menu offset-y>
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          dark outlined
          v-bind="attrs"
          v-on="on"
        >
          $ US Dollar
          <v-icon right size="10">fas fa-chevron-down</v-icon>
        </v-btn>
      </template>
      <v-list class="mt-3">
        <v-list-item
          v-for="(item, index) in items"
          :key="index"
        >
          <v-list-item-title>{{ item.title }}</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-menu>
    <v-menu offset-y>
      <template v-slot:activator="{ on, attrs }">
        <v-btn
          dark outlined
          v-bind="attrs"
          v-on="on"
        >
          English
          <v-icon right size="10">fas fa-chevron-down</v-icon>
        </v-btn>
      </template>
      <v-list class="mt-3">
        <v-list-item
          v-for="(item, index) in items"
          :key="index"
        >
          <v-list-item-title>{{ item.title }}</v-list-item-title>
        </v-list-item>
      </v-list>
    </v-menu>
    <v-spacer></v-spacer>
       <v-btn icon class="m-3">
        <v-icon>mdi-instagram</v-icon>
      </v-btn>
      <v-btn icon class="m-3">
        <v-icon>mdi-facebook</v-icon>
      </v-btn>
      <v-btn icon class="m-3">
        <v-icon>mdi-twitter</v-icon>
      </v-btn>
    </v-app-bar>
</template>
<script>
export default {
  data: () => ({
    items: [
      { title: 'Euro' },
      { title: 'Pound' },
      { title: 'Sterling' },
      { title: '$ US Dolla' }
    ]
  })
}
</script>
