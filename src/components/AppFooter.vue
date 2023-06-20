<script>

</script>

<template>
    <div class="container2">
        <div class="row">
        <!-- creo la lista con i link delle varie pagine -->
            <img src="../assets/buy-comics-digital-comics.png" alt="Img Digital Comic">
            <span>DIGITAL COMICS</span>
            <img src="../assets/buy-comics-merchandise.png" alt="Img Merch">
            <span>DC MERCHANDISE</span>
            <img src="../assets/buy-comics-subscriptions.png" alt="Img Sub">
            <span>SUBSCRIPTION</span>
            <img id="geo" src="../assets/buy-comics-shop-locator.png" alt="Img Shop Location">
            <span>COMIC SHOP LOCATOR</span>
            <img id="card" src="../assets/buy-dc-power-visa.svg" alt="Img Digital Comic">
            <span>DC POWER VISA</span>
        </div>
    </div>
    <div class="container">
        <div class="row">
            <div class="flex">
                <ul>  
                    <li><a href="#"><h4>DC COMICS</h4></a></li>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">TV</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#"><h4>SHOP</h4></a></li>
                    <li><a href="#">Shop DC</a></li>
                    <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
                <ul>  
                    <li><a href="#"><h4>DC</h4></a></li>
                    <li><a href="#">Terms Of Use</a></li>
                    <li><a href="#">Privacy policy (new)</a></li>
                    <li><a href="#">AD Choices</a></li>
                    <li><a href="#">Advertising</a></li>
                    <li><a href="#">Jobs</a></li>
                    <li><a href="#">Subscription</a></li>
                    <li><a href="#">Talent Workshop</a></li>
                    <li><a href="#">CPSC Certificates</a></li>
                    <li><a href="#">Ratings</a></li>
                    <li><a href="#">Shop Help</a></li>
                    <li><a href="#">Contact Us</a></li>
                </ul>
                <ul>  
                    <li><a href="#"><h4>SITES</h4></a></li>
                    <li><a href="#">DC</a></li>
                    <li><a href="#">MAD Magazine</a></li>
                    <li><a href="#">DC Kids</a></li>
                    <li><a href="#">DC Universe</a></li>
                    <li><a href="#">DC Power Visa</a></li>
                </ul>
            </div>
            <div class="logofoot">
                <img src="../assets/dc-logo-bg.png" alt="Logo DC Big">
            </div>
        </div>
    </div>
    <div class="container3">
        <div class="row">
            <div class="sign">
            <button>SIGN-UP NOW!</button>
            </div>
            <div class="follow_button">
                <h3>FOLLOW US</h3>
                    <a href="#"><img src="../assets/footer-facebook.png" alt="Facebook"></a>
                    <a href="#"><img src="../assets/footer-twitter.png" alt="Twitter"></a>
                    <a href="#"><img src="../assets/footer-youtube.png" alt="Youtube"></a>
                    <a href="#"><img src="../assets/footer-pinterest.png" alt="Pinterest"></a>
                    <a href="#"><img src="../assets/footer-periscope.png" alt="Periscope"></a>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use '../styles/generals.scss' as *;

    .container{
        background-image: url(../../public/footer-bg.jpg);
        background-size: cover;
        background-repeat: no-repeat;
        display: flex;
        align-items: center;

        .row{
            display: flex;
            justify-content: space-between;
        }

        .flex{
            display: flex;
            justify-content: space-between;
        }

        ul{
            list-style-type: none;
            padding: 50px 30px 40px 0;

            li{
                line-height: 1rem;
                h4{
                    font-size: 20px;
                    color: #fff;
                    margin: 15px 0;
                }

                a{
                    color: #959595;
                    text-decoration: none;
                    font-size: 13px;
                    font-weight: 400;
                }
            }
        }

        .logofoot img {
            width: 90%;

        }
    }

    .container2 {
        width: 100%;
        background: #0282f9;
        padding: 40px 0;
    }
    
    .container2 .row{
        display: flex;
        align-items: center;
        justify-content: space-between;

        img{
            display: flex;
            width: 6%;
            margin-right: 10px;
        }

        #geo{
            width: 4%;
        }   

        #card{
            width: 6%;
        }

        span{
        display: flex;
        align-items: center;
        font-size: 14px;
        color: #fff;
        margin: 20px;
        } 
    }

    .container3 {
        width: 100%;
        background: #303030;
        padding: 40px 0;

        .row{
            display: flex;
            justify-content: space-between;
        }

        button{
            font-size: 18px;
            font-weight: 500;
            color: #fff;
            border: 4px solid #0282f9;
            padding: 20px;
            background: #303030;
        }

        .follow_button{
            display: flex;
            justify-content: space-between;
            align-items: center;
            
            h3{
                font-size: 20px;
                font-weight: 700;
                color: #0282f9;
                margin-right: 15px;
            }

            a{
                padding: 0 10px;
            }
        }

    }

</style>
