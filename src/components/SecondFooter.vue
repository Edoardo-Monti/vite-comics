<script>

export default{
    name: "SecondFooter",
}

</script>
<template>
    <div class="box">
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
        </div>
        <div></div>
        <div></div>
    </div>

</template>
<style lang="scss" scoped>

.box{
    height:500px;
    background-image: url("/img/footer-bg.jpg");
    background-repeat: no-repeat;
    background-size: fill;
    display: flex;
    justify-content: flex-start;
    align-items: center;
}
</style>