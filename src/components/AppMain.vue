<script>
export default {
    name:'AppMain'
}
</script>

<template>
  <main class="main-top">
    <div class="container ">
      <h1>-->CONTENT GOES HERE</h1>
    </div>
    
  </main>
  <main class="main-footer">
    <div class="container">
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

  </main>
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

  .main-footer{
    background-color: var(--primary-color);
    padding: 30px 0;
  }
  
</style>