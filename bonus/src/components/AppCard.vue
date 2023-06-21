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
        <h4>{{ mybooks.series }}</h4>
        <p><strong>Type: {{ mybooks.type }}</strong></p>
    </div>
</template>

<style lang="scss" scoped>
    
    img{
        width: 250px;
        height: 250px;
        padding: 20px;
    }

    h4, p{
        font-weight: 700;
        color: #fff;
        padding:0 20px; 
    }
    p{
        font-size: 12px;
    }
</style>