<script>

</script>

<template>
    <div class="container">
        <div class="row">
            <!-- <ul>
               
                <li>
                    <a href="#"><img src="../assets/buy-comics-digital-comics.png" alt="Img Digital Comic">DIGITAL COMICS</a>
                </li>
                <li>
                    <a href="#"><img src="../assets/buy-comics-merchandise.png" alt="Img Merch">DC MERCHANDISE</a>
                </li>
                <li>
                    <a href="#"><img src="../assets/buy-comics-subscriptions.png" alt="Img Sub">SUBSCRIPTION</a>
                </li>
                <li>
                    <a href="#"><img src="../assets/buy-comics-shop-locator.png" alt="Img Shop Location">COMIC SHOP LOCATOR</a>
                </li>
                <li>
                    <a href="#"><img src="../assets/buy-dc-power-visa.svg" alt="Img Digital Comic">DC POWER VISA</a>
                </li>
            </ul> -->
            <img src="../assets/dc-logo-bg.png" alt="Logo DC Big">
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use '../styles/generals.scss' as *;

    .container{
        background-image: url(../../public/footer-bg.jpg);
        display: flex;
        align-items: center;
        padding: 40px 0;
        height: 300px;
    }

    .row img{
        width: 30%;
        rotate: (-5deg);
    }

    // ul{
    //     list-style-type: none;
    //     display: flex;
    //     align-items: center;
    //     justify-content: space-around;

    //     li{
    //         display: flex;
    //         align-items: center;
    //         padding: 10px;

    //         a{
    //             text-decoration: none;
    //             font-size: 15px;
    //             color: #fff;
    //             display: flex;
    //             align-items: center;
    //         }
    //     }
    // }

</style>