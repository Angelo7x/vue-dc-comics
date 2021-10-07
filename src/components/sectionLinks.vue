<template>
  <section>
      <div class="container">
          <ul>
              <li>
                  <img src="../assets/img/buy-comics-digital-comics.png" alt="dg">
                  <a href="#">DIGITAL COMICS</a>
              </li>
              <li>
                  <img src="../assets/img/buy-comics-merchandise.png" alt="merch">
                  <a href="#">DC MERCANDISE</a>
              </li>
              <li>
                  <img src="../assets/img/buy-comics-subscriptions.png" alt="sub">
                  <a href="#">SUBSCRIPTION</a>
              </li>
              <li>
                  <img src="../assets/img/buy-comics-shop-locator.png" alt="shop">
                  <a href="#">COMIC SHOP LOCATOR</a>
              </li>
              <li>
                  <img src="../assets/img/buy-dc-power-visa.svg" alt="visa">
                  <a href="#">DC POWER VISA</a>
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

                a {
                    text-decoration: none;
                    color: white;
                    vertical-align: middle;
                }
                img {
                    vertical-align: middle;
                    height: 100px;
                    padding: 10px;
                }
            }
        }
    }
</style>