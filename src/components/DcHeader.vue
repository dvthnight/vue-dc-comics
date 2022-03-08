<template>
    <header>
        <div class="container">
            <figure class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </figure>

            <ul class="nav-list">
                <li class="nav-element"><a href="#">Characters</a></li>
                <li class="nav-element"><a href="#">Comics</a></li>
                <li class="nav-element"><a href="#">Movies</a></li>
                <li class="nav-element"><a href="#">Tv</a></li>
                <li class="nav-element"><a href="#">Games</a></li>
                <li class="nav-element"><a href="#">Collectibles</a></li>
                <li class="nav-element"><a href="#">Videos</a></li>
                <li class="nav-element"><a href="#">Fans</a></li>
                <li class="nav-element"><a href="#">News</a></li>
                <li class="nav-element"><a href="#">Shop</a></li>
            </ul>
        </div>
    </header>
</template>

<script>
    export default{

        data() {
            return{

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
    }

    .nav-list{
        display: flex;
        text-transform: uppercase;
        gap: 30px;


    }

    .nav-element{

    }

    li{
        list-style: none;
    }

    a{
        text-decoration: none;
        color: currentColor;
    }
</style>
