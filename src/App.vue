<template>
  <v-app>
    <v-main>
      <Navbar/>
      <Dashboard/>
      <Footer/>
    </v-main>
  </v-app>
</template>

<script>
import Navbar from './components/Navbar.vue'
import Dashboard from './components/Dashboard.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',

  components: {
    Navbar,
    Dashboard,
    Footer,
  },

  data: () => ({
    //
  }),
}
</script>
