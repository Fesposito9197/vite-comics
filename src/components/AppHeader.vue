<script>
export default {
    name:'AppHeader',
    data(){
        return{
            links:[
                'Characters',
                'Comics',
                'Movies',
                'TV',
                'Games',
                'Collectibles',
                'Videos',
                'Fans',
                'News',
                'Shop'
            ]
        }
    }
}
</script>

<template>
  <header>
    <div class="container d-flex j-content-sb">
        <img src="../assets/dc-logo.png" alt="logo">
        <nav>
            <ul>
                <li v-for="link in links"><a href="#">{{link}}</a></li>
                
            </ul>
        </nav>
    </div>
  </header>
</template>

<style lang="scss" scoped>
    header{
        padding: 10px 0;
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
                color: var(--secondary-color);
                font-weight: 700;
            }
        }
    }
</style>