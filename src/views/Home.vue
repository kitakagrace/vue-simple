<template>
  <div class="home">
    <Navbar msg="Welcome to Your Vue.js App"/>
    <h1>This is the home page</h1>
  </div>
  
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'

export default {
  name: 'Home',
  components: {
    Navbar
  }
}
</script>
