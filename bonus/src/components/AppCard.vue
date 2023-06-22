<script>
export default {
    /* CON LA PROPS DICO CHE MYBOOKS E' UN OGGETTO */
    props:{
        mybooks: Object
    }
}
</script>

<template>
    <!-- Inserisco gli elementi dell'array nel template per farli visualizzare -->
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