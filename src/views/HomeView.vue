<template>
  <V-app :style="{ background: $vuetify.theme.themes.dark.background  }">
    <Navbar />
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
