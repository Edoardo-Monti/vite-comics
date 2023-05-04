<script>

export default{
    name: "Card",
    props:["prompsCard"]
}

</script>
<template>
    <div class="cardDc">
        <img :src="prompsCard.thumb" alt="">
        <h3>{{ prompsCard.series }}</h3>
        <span>{{ prompsCard.price }}</span>
    </div>
</template>
<style scoped lang="scss">
    
    .cardDc{
        width: calc(100% / 6);
        margin-bottom: 40px;
        img{
            width: 200px;
            height: 200px;
        }
        h3{
            color: white;
            font-size: 15px;
            margin-right: 40px;
        }
        span{
            color: white;
        }
    }
</style>