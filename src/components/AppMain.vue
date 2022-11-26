<script>
import SectionComics from "./SectionComics.vue";

export default {
  components:{
    SectionComics
  },
    name:'AppMain'
}
</script>

<template>
  <div class="jumbotron"></div>

  <div class="main-top">
    <SectionComics/>
    
  </div>
  <div class="main-bottom">
    <div class="container d-flex">
      <div class="card">
        <img src="../assets/buy-comics-digital-comics.png" alt="">
        <h3>DIGITAL COMICS</h3>
      </div>
      <div class="card">
        <img src="../assets/buy-comics-merchandise.png" alt="">
        <h3>DC MERCHANDISE</h3>
      </div>
      <div class="card">
        <img src="../assets/buy-comics-subscriptions.png" alt="">
        <h3>SUBSCRIPTION</h3>
      </div>
      <div class="card">
        <img src="../assets/buy-comics-shop-locator.png" alt="">
        <h3>COMIC SHOP LOCATOR</h3>
      </div>
      <div class="card">
        <img src="../assets/buy-dc-power-visa.svg" alt="">
        <h3> DC POWER VISA </h3>
      </div>
    </div>

  </div>
</template>

<style lang="scss" scoped>
  .main-top{
    background-color: var(--secondary-color);
    .container{
      
      h1{
        color: var(--white-text);
        padding: 40px 0;
      }
    }
  }
  .jumbotron{
    background-image: url(../assets/jumbotron.jpg);
    
    height: 50vh;
    
    background-size: cover;
    
  }
  .main-bottom{
    background-color: var(--primary-color);
    padding: 30px 0;
  }
  
</style>