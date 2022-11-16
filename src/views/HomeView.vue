<template>
  <V-app :style="{ background: $vuetify.theme.themes.dark.background }">
    <Navbar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img
            src="https://cdn.vuetifyjs.com/images/backgrounds/vbanner.jpg"
            height="300px"
          ></v-img>
        </v-col>
      </v-row>
    </v-container>
  </V-app>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  name: 'Home',

  components: {
    Navbar,
  },
}
</script>
