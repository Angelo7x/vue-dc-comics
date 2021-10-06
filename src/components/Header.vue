<template>
  <header class="container">
      <img src="../assets/img/dc-logo.png" alt="">
      <ul>
        <li v-for="(elm, index) in navBar" :key="index"><a href="#"></a>{{elm.text}}</li>
      </ul>
  </header>
</template>

<script>
export default {
    name:'Header',
    data() {
      return {
        navBar: [
          {
            text: "CHARACTERS",
            url: "#",
            current: false
          },
          {
            text: "COMICS",
            url: "#",
            current: true
          },
          {
            text: "MOVIES",
            url: "#",
            current: false
          },
          {
            text: "TV",
            url: "#",
            current: false
          },
          {
            text: "GAMES",
            url: "#",
            current: false
          },
          {
            text: "COLLECTIBLES",
            url: "#",
            current: false
          },
          {
            text: "VIDEOS",
            url: "#",
            current: false
          },
          {
            text: "FANS",
            url: "#",
            current: false
          },
          {
            text: "NEWS",
            url: "#",
            current: false
          },
          {
            text: "SHOP",
            url: "#",
            current: false
          }
        ]
      }
    }
}
</script>

<style lang="scss" scoped>
  header{
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 130px;
  }

  ul {
    list-style: none;
      li {
        display: inline-block;
        padding: 20px;

      }
  }
</style>