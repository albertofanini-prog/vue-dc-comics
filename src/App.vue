<template>
  <div id="app">
    <NavBar/>
    <ContentSection/>
    <BlueSection/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import ContentSection from './components/ContentSection.vue'
import BlueSection from './components/BlueSection.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    ContentSection,
    BlueSection
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
*{
  margin: 0 auto;
}
</style>
