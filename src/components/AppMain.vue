<script>

</script>

<template>
    <div class="container">
        <div class="row">
            <h2>--&gt; CONTENT HERE &lt;--</h2>
        </div>
    </div>
    <div class="container blue">
        <div class="row">
            <ul>
                <!-- creo la lista con i link delle varie pagine -->
                <li>
                    <a href="#"><img src="../assets/buy-comics-digital-comics.png" alt="Img Digital Comic">DIGITAL COMICS</a>
                </li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss" scoped>
    @use '../styles/generals.scss' as *;
    .container{
        background-color: black;
        display: flex;
        align-items: center;
        padding: 50px 0;
    }

    .container.blue {
        background: #0282f9;
        padding: 50px 0;
    }

    h2{
        color: #fff;
    }

    ul{
        list-style-type: none;
        display: flex;
        align-items: center;

        li{
            display: flex;
            align-items: center;
            padding: 10px;

            a{
                text-decoration: none;
                font-size: 15px;
                color: #fff;
                display: flex;
                align-items: center;
            }
        }
    }

    img{
        width: 50px;
        margin-right: 15px;
    }
</style>