<template>
  <div>
    <NavBar :ishome="false"></NavBar>
    <div class="pt-24">hello there</div>
  </div>
</template>

<script>
import NavBar from '../components/NavBar'

export default {
  name: 'Portfolio',
  components: {
    NavBar
  }
}
</script>

<style lang="scss" scoped></style>
