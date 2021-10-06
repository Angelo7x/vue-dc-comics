<template>
  <section>
      <div class="container">
          <ul>
              <li>
                  <img src="../assets/img/buy-comics-digital-comics.png" alt="dg">
                  <a href="#">Digital Comics</a>
              </li>
              <li>
                  <img src="../assets/img/buy-comics-digital-comics.png" alt="dg">
                  <a href="#">Digital Comics</a>
              </li>
              <li>
                  <img src="../assets/img/buy-comics-digital-comics.png" alt="dg">
                  <a href="#">Digital Comics</a>
              </li>
              <li>
                  <img src="../assets/img/buy-comics-digital-comics.png" alt="dg">
                  <a href="#">Digital Comics</a>
              </li>
              <li>
                  <img src="../assets/img/buy-comics-digital-comics.png" alt="dg">
                  <a href="#">Digital Comics</a>
              </li>
          </ul>
      </div>
  </section>
</template>

<script>
export default {
    name: "SectionLinks"
}
</script>

<style lang="scss" scoped>
    section {
        background-color: #0282f9;
        height: 200px;
        ul {
            list-style: none;
            display: flex;
            justify-content: space-around;
            align-items: center;
            li {
                padding: 30px;
                line-height: 200px;
            }
        }
    }
</style>