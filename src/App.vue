<template>
  <div id="app">
    <Hero/>
    <Follow/>
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import Follow from './components/Follow.vue'

export default {
  name: 'App',
  components: {
    Hero,
    Follow
  }
}
</script>

<style lang="scss">
@import "@/assets/style.scss";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}


</style>
