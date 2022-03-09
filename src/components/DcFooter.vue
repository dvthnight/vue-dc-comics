<template>
    <footer>
            <div class="container">
            <div class="blue_nav">
               <div class="container">

                   <ul class="ul_blue_nav">
                       <li class="el_blue_nav">
                           <figure >
                               <img class="img_blue_nav" src="../assets/img/buy-comics-digital-comics.png" alt="">
                           </figure>
                           <a href="#" class="a_blue_nav">Digital comics</a>
                        </li>
                       <li class="el_blue_nav">
                            <figure >
                               <img class="img_blue_nav" src="../assets/img/buy-comics-merchandise.png" alt="">
                           </figure>
                           <a href="#" class="a_blue_nav">Dc merchandise</a>
                        </li>
                       <li class="el_blue_nav">
                            <figure >
                               <img class="img_blue_nav"  src="../assets/img/buy-comics-shop-locator.png" alt="">
                           </figure>
                           <a href="#" class="a_blue_nav">Subscription</a>
                        </li>
                       <li class="el_blue_nav">
                            <figure>
                               <img class="img_blue_nav" src="../assets/img/buy-comics-subscriptions.png" alt="">
                           </figure>
                           <a href="#" class="a_blue_nav">Comic shop locator</a>
                        </li>
                       <li class="el_blue_nav">
                            <figure >
                               <img class="img_blue_nav power_visa" src="../assets/img/buy-dc-power-visa.svg" alt="">
                           </figure>
                           <a href="#" class="a_blue_nav">Dc power visa</a>
                        </li>
                   </ul>

                </div>
            </div>
                <div class="footer_centrale">
                    <div class="container">

                        <div class="centrale_colonne">
                            <div class="colonna1 col_foot">
                                <div class="ul_1_sx col_foot">
                                    <h3 class="titolo_colonne_footer">Dc Comics</h3>
                                    <li class="el_foot_centr"><a href="#">Characters</a></li>
                                    <li class="el_foot_centr"><a href="#">Comics</a></li>
                                    <li class="el_foot_centr"><a href="#">Movies</a></li>
                                    <li class="el_foot_centr"><a href="#">TV</a></li>
                                    <li class="el_foot_centr"><a href="#">Games</a></li>
                                    <li class="el_foot_centr"><a href="#">Videos</a></li>
                                    <li class="el_foot_centr"><a href="#">News</a></li>
                                </div>

                                <div class="ul_2_sx col_foot">
                                    <h3 class="titolo_colonne_footer">Shop</h3>
                                    <li class="el_foot_centr"><a href="#">Shop DC</a></li>
                                    <li class="el_foot_centr"><a href="#">Shop DC Collectibles</a></li>
                                
                                </div>
                            </div>

                            <div class="colonna2 col_foot">
                                <h3 class="titolo_colonne_footer">DC</h3>
                                <li class="el_foot_centr"><a href="#">Terms Of Use</a></li>
                                <li class="el_foot_centr"><a href="#">Privacy policy (New)</a></li>
                                <li class="el_foot_centr"><a href="#">Ad Choices</a></li>
                                <li class="el_foot_centr"><a href="#">Advertising</a></li>
                                <li class="el_foot_centr"><a href="#">Jobs</a></li>
                                <li class="el_foot_centr"><a href="#">Subscriptions</a></li>
                                <li class="el_foot_centr"><a href="#">Talent Workshop</a></li>
                                <li class="el_foot_centr"><a href="#">CPSC Certicates</a></li>
                                <li class="el_foot_centr"><a href="#">Ratings</a></li>
                                <li class="el_foot_centr"><a href="#"></a>Shop Help</li>
                                <li class="el_foot_centr"><a href="#">Contact Us</a></li>
                            </div>

                            <div class="colonna3 col_foot">
                                <h3 class="titolo_colonne_footer">Sites</h3>
                                <li class="el_foot_centr"><a href="#">DC</a></li>
                                <li class="el_foot_centr"><a href="#">MAD Magazine</a></li>
                                <li class="el_foot_centr"><a href="#">DC Kids</a></li>
                                <li class="el_foot_centr"><a href="#">DC Universe</a></li>
                                <li class="el_foot_centr"><a href="#">DC Power Vista</a></li>
                            </div>

                        </div>

                        <div class="centrale_logo">
                            
                        </div>
                    </div>
                </div>
            <div class="footer_basso">
                <div class="container">

                </div>
            </div>
        </div>
    </footer>
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

    img{
        width: 100%;
    }

    li{
        list-style: none;
    }

    a{
        text-decoration: none;
        color: currentColor;
    }

    .blue_nav{
        background-color: rgb(29, 121, 239);
        width: 100vw;
        height: 150px;

        .container{
            width: 1280px;
            margin: 0 auto;
            display: flex;
            flex-wrap: wrap;
            height: 100%;

            

            .ul_blue_nav{
                display: flex;
                align-items: center;
                height: 100%;
                width: 100%;
                justify-content: space-between;


                .el_blue_nav{
                    color: white;
                    display: flex;
                    align-items: center;
                    gap: 20px;
                    
                    .img_blue_nav{
                        height: 50px;
                    }

                    .power_visa{
                        width: 50px;
                    }
                }
                .a_blue_nav{
                    height: 100%;
                    text-transform: uppercase;
                    // font-size: 15px;
                }
                

               
            }






        }

    }

    .footer_centrale{
        background-image: url("../assets/img/footer-bg.jpg");
        height: 370px;

        .container{
            width: 1280px;
            margin: 0 auto;
            display: flex;
            flex-wrap: wrap;
            height: 100%;
            justify-content: space-between;

            

            .centrale_logo{
                background-image: url("../assets/img/dc-logo-bg.png");
                height: 100%;
                width: 500px;
                background-repeat: no-repeat;
                background-size: cover;
                background-position-y: center;
            }

            .centrale_colonne{
                display: flex;
                gap: 30px;
                padding: 30px;

                .titolo_colonne_footer{
                    font-size: 25px;
                    margin-bottom: 10px;
                    color: white;
                }

                .el_foot_centr{
                    color: rgb(138, 138, 138);
                }

                .col_foot{
                    margin-bottom: 10px;
                }
            }

        }
    }


    .footer_basso{
        height: 110px;
        background-color: rgb(42, 42, 42);
    }

</style>
