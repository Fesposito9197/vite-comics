<script>
export default {
    name:'AppHeader'
}
</script>

<template>
  <header>
    <div class="container d-flex j-content-sb">
        <img src="../assets/dc-logo.png" alt="logo">
        <nav>
            <ul>
                <li><a href="">Characters</a></li>
                <li><a href="">Comics</a></li>
                <li><a href="">Movies</a></li>
                <li><a href="">TV</a></li>
                <li><a href="">Games</a></li>
                <li><a href="">Collectibles</a></li>
                <li><a href="">Videos</a></li>
                <li><a href="">Fans</a></li>
                <li><a href="">News</a></li>
                <li><a href="">Shop</a></li>
            </ul>
        </nav>
    </div>
  </header>
</template>

<style lang="scss" scoped>
    header{
        padding: 20px 0;
    }
    
    ul{
        list-style: none;
        display: flex;
        li{
            display: inline-block;
            padding: 0 10px;

            a{
                text-decoration: none;
                line-height: 103px;
            }
        }
    }
</style>