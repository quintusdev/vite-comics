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
        <p><strong>Type: {{ mybooks.type }}</strong></p>
    </div>
</template>

<style lang="scss" scoped>
    .card{
        display: flex;
        justify-content: space-between;
        align-items: center;
        border: 2px solid #fff;

        img{
            width: 250px;
            height: 250px;
            padding: 5px 5px;
        }

        span, p{
            padding: 30px;
            color: #fff;
            font-size: 15px;
            font-weight: 700;
        }
    }
</style>