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

    

    
</style>
