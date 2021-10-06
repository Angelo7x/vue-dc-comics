<template>
  <div id="app">
    <Header/>
    <SectionHero/>
    <SectionCards/>
    <SectionLinks/>
    <Footer/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Footer from "./components/Footer.vue";
import SectionHero from "./components/SectionHero.vue";
import SectionCards from "./components/SectionCards.vue";
import SectionLinks from "./components/SectionLinks.vue";


export default {
  name: 'App',
  components: {
    Header,
    SectionHero,
    SectionCards,
    SectionLinks,
    Footer
  }
}
</script>

<style lang="scss">
@import "./assets/style/common";
</style>
