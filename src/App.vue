<template>
  <div id="app">
    <div class="container">
      <Header/>
    </div>
    <main>
      <sectionHero/>
      <sectionCards/>
      <sectionLinks/>
    </main>
      <Footer/>
    </div>
</template>

<script>
import Header from "./components/Header.vue";
import sectionHero from "./components/sectionHero.vue"
import sectionCards from "./components/sectionCards.vue"
import sectionLinks from "./components/sectionLinks.vue"
import Footer from "./components/Footer.vue"

export default {
  name: 'App',
  components: {
    Header,
    sectionHero,
    sectionCards,
    sectionLinks,
    Footer
  }
}
</script>

<style lang="scss">
@import "./assets/style/common";
</style>
