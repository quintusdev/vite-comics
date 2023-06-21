<script>
export default {
    props:{
        mybooks: Object
    }
}
</script>

<template>
    <div class="card">
        <img :src="mybooks.thumb">
        <span>{{ mybooks.series }}</span>
        <span><strong>Type: {{ mybooks.type }}</strong></span>
        <p>Price: {{ mybooks.price }}</p>
    </div>
</template>

<style lang="scss" scoped>
    
    img{
        width: 160px;
        height: 150px;

        img:hover{
            opacity: 0.5;
        }
    }

    span, p{
        display: flex;
        color: #fff;
        font-size: 15px;
        font-weight: 700;
        padding-left: 15px;
        margin: 5px 0;
    }
</style>