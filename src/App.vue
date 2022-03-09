<template>
  <div id="app">
    <NavBar/>
    <JumbotronSlider/>
    <ContentSection/>
    <BlueSection/>
    <LinksSection/>
    <SocialBar/>
  </div>
</template>

<script>
import NavBar from './components/NavBar.vue'
import ContentSection from './components/ContentSection.vue'
import BlueSection from './components/BlueSection.vue'
import LinksSection from './components/LinksSection.vue'
import SocialBar from './components/SocialBar.vue'
import JumbotronSlider from './components/jumbotronSlider.vue'

export default {
  name: 'App',
  components: {
    NavBar,
    JumbotronSlider,
    ContentSection,
    BlueSection,
    LinksSection,
    SocialBar
  },
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
