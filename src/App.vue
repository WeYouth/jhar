<template>
  <div id="app">
    <Hero/>
    <About/>
    <Follow/>
    <Footer/>
  </div>
</template>

<script>
import Hero from './components/Hero.vue'
import About from './components/About.vue'
import Follow from './components/Follow.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Hero,
    About,
    Follow,
    Footer
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
