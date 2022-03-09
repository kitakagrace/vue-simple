<template>

  <v-container>
    <Navbar msg="Welcome to Your Vue.js App"/>
    <v-img
  lazy-src="https://picsum.photos/id/11/10/6"
  max-height="146"
  max-width=""
  src="https://picsum.photos/id/11/500/300"
></v-img>
<h1>About Us</h1>
  </v-container>
</template>

<script>
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Home',
  components: {
    Navbar
  }
}

</script>