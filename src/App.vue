<template>
  <div id="app">
    <NavBar />
    <router-view />
    <Footer />
  </div>
</template>

<script>
import NavBar from './components/NavBar'
import Footer from './components/Footer'

export default {
  name: 'MainApp',
  components: {
    NavBar,
    Footer
  }
}
</script>
