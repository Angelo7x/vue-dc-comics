<template>
  <footer>
      <div class="footer-top">
        <div class="container">
          <div class="footer-left"></div>
          <div class="footer-right"></div>
        </div>
      </div>
      <div class="footer-bot">
        <div class="container">
          <div class="btn-left">
            <button class="btn"><a href="#">SIGN-UP NOW!</a></button>
          </div>
          <div class="socials-right">
            <ul>
              <li><a href="#"><h3>FOLLOW US</h3></a></li>
              <li><a href="#"><img src="../assets/img/footer-facebook.png" alt=""></a></li>
              <li><a href="#"><img src="../assets/img/footer-twitter.png" alt=""></a></li>
              <li><a href="#"><img src="../assets/img/footer-youtube.png" alt=""></a></li>
              <li><a href="#"><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
              <li><a href="#"><img src="../assets/img/footer-periscope.png" alt=""></a></li>
            </ul>
          </div>
        </div>
      </div>
  </footer>
</template>

<script>
export default {
    name: "Footer"
}
</script>

<style lang="scss" scoped>
  .footer-top {
    background-image: url("../assets/img/footer-bg.jpg");
    height: 500px;
    width: 100%;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    .container {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
  }

  .footer-left {

  }

  .footer-right {
    background-image: url("../assets/img/dc-logo-bg.png");
    height: 500px;
    width: 50%;
    background-repeat: no-repeat;
  }



  .footer-bot {
    height: 100px;
    background-color: #303030;
    .container {
      display: flex;
      justify-content: space-between;
      .btn-left {
        line-height: 100px;
        .btn {
          a {
            text-decoration: none;
            color: white;
            border: 2px solid #0282f9;
            padding: 15px;
            background-color: #303030;
          }
          
        }
      }
    }
  }

  .socials-right {
    a {
      text-decoration: none;
    }
    h3 {
      color: #0282f9;
    }
    ul {
      list-style: none;
      line-height: 100px;
      li {
        display: inline-block;
        padding: 10px;
      }
    }
  }
</style>