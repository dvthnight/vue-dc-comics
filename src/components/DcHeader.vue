<template>
    <header>
        <div class="container">
            <figure class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </figure>

            <ul class="nav-list">
                <li class="nav-element" v-for="(el,i) in navList" :key="i" :class="{'active': true == el.active} "><a href="#">{{el.text}}  </a></li>
                
            </ul>
        </div>
    </header>
</template>

<script>
    export default{

        data() {
            return{
                navList:[
                    {
                        text: "Characters",
                    },

                    {
                        text: "Comics",
                        active: true,
                    },

                    {
                        text: "Movies",
                    },

                    {
                        text: "Tv",
                    },

                    {
                        text: "Games",
                    },
                    {
                        text: "Collectibles",
                    },

                    {
                        text: "Videos",
                    },

                    {
                        text: "Fans",
                    },

                    {
                        text: "News",
                    },

                    {
                        text: "Shop",
                    },
                ]
            }
        }
    }
    
</script>

<style scoped lang="scss">
    .container{
        max-width: 1280px;
        margin: 0 auto;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        align-items: center;
        padding: 20px;
    }

    .nav-list{
        display: flex;
        text-transform: uppercase;
        gap: 30px;
        font-weight: 700;

            .nav-element{
                &.active{
                    color: rgb(29, 121, 239);
                    position: relative;
                }

                &.active::after{
                    content: "";
                    display: block;
                    background-color: rgb(29, 121, 239);
                    height: 5px;
                    width: 65px;
                    position: absolute;
                    top: 81px;
                }

            }

    }

    // .nav-element{

    // }

    li{
        list-style: none;
    }

    a{
        text-decoration: none;
        color: currentColor;
    }
</style>
