<template>
  <div id="app">
    <NavBar/>
    <ContentSection/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import ContentSection from './components/ContentSection.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    ContentSection
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
