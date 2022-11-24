<script>
export default {
    name:'AppFooter'
}
</script>

<template>
  <div class="footer-top">
    <div class="container d-flex bg-logo">
      <div>
        <ul class="footer-list">
          <h2>DC COMICS</h2>
          <li><a href="#">Characters</a></li>
          <li><a href="#">Comics</a></li>
          <li><a href="#">Movies</a></li>
          <li><a href="#">TV</a></li>
          <li><a href="#">Games</a></li>
          <li><a href="#">Videos</a></li>
          <li><a href="#">News</a></li>
        </ul>
        <ul class="footer-list">
          <h2>SHOP</h2>
          <li><a href="#">Shop DC</a></li>
          <li><a href="#">Shop DC Collectibles</a></li>
        </ul>
      </div>
      <div>
        <ul class="footer-list">
          <h2>DC</h2>
          <li><a href="#">Terms Of Use</a></li>
          <li><a href="#">Privacy policy (New)</a></li>
          <li><a href="#">Ad Choices</a></li>
          <li><a href="#">Advertising</a></li>
          <li><a href="#">Jobs</a></li>
          <li><a href="#">Subscriptions</a></li>
          <li><a href="#">Talent Workshops</a></li>
          <li><a href="#">CPSC Certificates</a></li>
          <li><a href="#">Ratings</a></li>
          <li><a href="#">Shop Help</a></li>
          <li><a href="#">Contact Us</a></li>
        </ul>
      </div>
      <div>
        <ul class="footer-list">
          <h2>SITES</h2>
          <li><a href="#">DC</a></li>
          <li><a href="#">MAD Magazine</a></li>
          <li><a href="#">DC Kids</a></li>
          <li><a href="#">DC Universe</a></li>
          <li><a href="#">DC Power Visa</a></li>
        </ul>
      </div>
      
    </div>
    
  </div>
  <div class="footer-bottom">
    <div class="container d-flex j-content-sb">
      <button>
        SIGN-UP NOW!
      </button>
      <div>
        <h3></h3>
        <img src="../assets/footer-facebook.png" alt="">
        <img src="../assets/footer-twitter.png" alt="">
        <img src="../assets/footer-youtube.png" alt="">
        <img src="../assets/footer-pinterest.png" alt="">
        <img src="../assets/footer-periscope.png" alt="">
      </div>

    </div>
  </div>
</template>

<style lang="scss" scoped>
  .footer-top{
    background-image: url(../assets/footer-bg.jpg) ;
    background-size: cover;
    background-repeat: no-repeat;
  }
    
  .footer-bottom{
    background-color: var(--footer-bg);
    padding: 30px;
  }
    
   
  .bg-logo{
    padding: 15px 0;
    background-image: url(../assets/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-position:right;
  }
    


  .footer-list{
    list-style: none;
    padding: 20px;
    h2{
      color: var(--white-text);
      padding-bottom: 10px;
    }
    a{
      color: var(--grey-text);
      text-decoration: none;
      display: inline-block;
      padding-bottom: 5px;
    }
  }



  
</style>