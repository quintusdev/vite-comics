<script>
export default{
    data() {
        return {
            navs: [
                {icon: '../src/assets/buy-comics-digital-comics.png', text: 'DIGITAL COMICS'},
                {icon: '../src/assets/buy-comics-merchandise.png', text: 'DC MERCHANDISE'},
                {icon: '../src/assets/buy-comics-subscriptions.png', text: 'SUBSCRIPTION'},
                {icon: '../src/assets/buy-comics-shop-locator.png', text: 'COMIC SHOP LOCATOR'},
                {icon: '../src/assets/buy-dc-power-visa.svg', text: 'DC POWER VISA'},
            ]
        }
    },
}
</script>

<template>
    <div class="container2">
        <div class="row">
            <div class="flex" v-for="(nav, index) in navs" :key="index">
                <img :src="nav.icon" alt="Img Icon Blue">
                <span>{{ nav.text }}</span>
            </div> 
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use '../styles/partials/variables' as*;
.container2 {
    display: flex;
    align-items: center;
    width: 100%;
    background: #0282f9;
    padding: 40px 0;
    
    .row{
        width: 70%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .flex{
            display: flex;
        }
        
        img{
            width: 55px;
            height: 70px;
            margin-right: 10px;
        }

        span{
        display: flex;
        align-items: center;
        font-size: 14px;
        color: #fff;
        margin: 20px;
        } 
    }
}
</style>