<script>
export default {
    name:'AppHeader',
    data(){
        return{
            
            links:[
                {
                    label:'Characters',
                    active:false,
                },
                {
                    label:'Comics',
                    active:true,
                },
                {
                    label:'Movies',
                    active:false,
                },
                {
                    label:'TV',
                    active:false,
                },
                {
                    label:'Games',
                    active:false,
                },
                {
                    label:'Collectibles',
                    active:false,
                },
                {
                    label:'Videos',
                    active:false,
                },
                {
                    label:'Fans',
                    active:false,
                },
                {
                    label:'News',
                    active:false,
                },
                {
                    label:'Shop',
                    active:false,
                }
               
            ]
        }
    },
    methods:{
       ChangeLink(index) {
            this.links.forEach((elm,i) => {
                if (i===index) {
                    elm.active = true
                }else{
                    elm.active=false
                }
            })
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
                <li v-for="(link , index) in links" :class="{active: link.active}" ><a href="#"   @click.prevent="ChangeLink(index)">{{link.label}}</a></li>
                
            </ul>
        </nav>
    </div>
  </header>
</template>

<style lang="scss" scoped>
    header{
        
        
    }
    img{
        padding: 10px 0;
    }
    ul{
        list-style: none;
        display: flex;
        li{
            display: inline-block;
            padding: 8px 10px;
            

            a{
                text-decoration: none;
                line-height: 103px;
                color: var(--secondary-color);
                font-weight: 700;
                position: relative;
            }
        }
    }
    .active{
       
        border-bottom: 5px solid var(--primary-color);
        a{
            color: var(--primary-color);
        }
        
    }
</style>