<script>

export default{
    name: 'FirstFooter',
    data(){
        return{
            info:[
                {
                    detail: "DIGITAL COMICS",
                    path: "/img/buy-comics-digital-comics.png"
                },
                {
                    detail: "DC MERCHANDISE", 
                    path: "/img/buy-comics-merchandise.png"
                },
                {
                    detail: "SUBSCRIPTION",
                    path: "/img/buy-comics-subscriptions.png"
                },
                {
                    detail: "COMIC SHOP LOCATOR",
                    path: "/img/buy-comics-shop-locator.png"
                },
                {
                    detail: "DC POWER VISA",
                    path: "/img/buy-dc-power-visa.svg"
                },
            ]
        }
    }
}

</script>
<template>
    <section>
        <div class="cont">
            <div v-for="(element, index) in info" :key="index">
                <img :src="element.path" alt="">
                <span>{{ element.detail }}</span>
            </div>

        </div>
    </section>
</template>
<style lang="scss" scoped>
    section{
        background-color: rgb(66, 66, 236);
        width: 100%;
        height: 150px;
        display: flex;
        align-items: center;
        .cont{
            width: 80%;
            margin: 0 auto;
            display: flex;
            justify-content: space-around;
            align-items: center;
            div{

                span{
                    color: white;
                    font-size: 12px;
                }
                img{
                    height: 60px;
                    font-size: 10px;
                    margin-right: 10px;
                    vertical-align: middle;
                }

            }
        }
    }
</style>