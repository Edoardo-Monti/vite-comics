<script>

export default{
    name: "SecondFooter",
}

</script>
<template>
    <div class="box">
        <div class="box-2">

            <div>
                <p>DC COMICS</p>
                <ul>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                <p>Shop</p>
                <ul>
                    <li>Shop DC</li>
                    <li>Shop DC Collectibles</li>
                </ul>
            </div>

            <div>
                <p>DC</p>
                <ul>
                    <li>Terms of use</li>
                    <li>Privacy policy (New)</li>
                    <li>Ad Choices</li>
                    <li>Adversting</li>
                    <li>Jobs</li>
                    <li>Subscription</li>
                    <li>Talent Workshop</li>
                    <li>CPSC Certificated</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </div>
            
            <div>
                <p>SITES</p>
                <ul>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>
                </ul>
            </div>

            
        </div>
        <img class="position" src="/img/dc-logo-bg.png" alt="">
    </div>

</template>
<style lang="scss" scoped>

.box{
    width: 100%;
    height:500px;
    background-image: url("/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: cover;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    .box-2{
        display: flex;
        position: relative;
        width: 80%;
        margin: 0 auto;
        div{
            margin-left: 30px;
            p{
                color: white;
                font-size: 20px;
                margin-top: 20px;
                margin-bottom: 10px;
            }
            ul{
                li{
                    color: gray;
                    font-size: 15px;
                    list-style-type: none;
                }
            }
        }
        .position{
            position: absolute;
            top: 0;
            right: 0;
        }
    }
}
</style>