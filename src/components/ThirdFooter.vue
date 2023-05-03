<script>

export default{
    name: 'ThirdFooter'
}

</script>
<template>
    <div id="box">
        <div class="w-80">
            <div class="btn">
                <button> SIGN-UP NOW!</button>
            </div>
            <div class="social">
                <span>FOLLOW US</span>
                <img src="/img/footer-facebook.png" alt="">
                <img src="/img/footer-twitter.png" alt="">
                <img src="/img/footer-youtube.png" alt="">
                <img src="/img/footer-pinterest.png" alt="">
                <img src="/img/footer-periscope.png" alt="">
            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
    #box{
        height: 120px;
        background-color: rgb(86, 86, 86);
        display: flex;
        align-items: center;
        position: relative;
        z-index: 4;
        .w-80{
            width: 80%;
            margin:0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            .btn{
                button{
                    border: 2px solid rgb(41, 41, 205);
                    background-color: transparent;
                    color: white;
                    padding: 10px;
                }
            }
            .social{
                display: flex;
                align-items: center;
                span{
                    color: rgb(41, 41, 205);
                }
                img{
                    margin-left: 10px;
                }
            }
        }
    }
</style>