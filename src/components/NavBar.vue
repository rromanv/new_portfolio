<template>
  <nav class="nav w-screen z-20 shadow-2xl bg-red-800 text-white">
    <div class="left">
      <span class="font-light text-3xl">
        My
        <span class="font-semibold">Portfolio</span>
      </span>
    </div>
    <div class="right">
      <router-link class="link" to="/">Home</router-link>
      <router-link class="link" to="/portfolio">Portfolio</router-link>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'NavBar'
}
</script>

<style lang="scss" scoped>
.nav {
  @apply h-24 fixed px-12 flex justify-between items-center;
}
.link {
  @apply px-2 font-semibold;
  &:hover {
    @apply text-yellow-500;
  }
}
</style>
