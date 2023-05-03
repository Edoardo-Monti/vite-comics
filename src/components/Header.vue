<script>
export default{
    name: "Header",
    data(){
        return{
            array:[
                {
                    nome: "CHARACTER",
                    current: false
                },
                {
                    nome: "COMICS",
                    current: false
                },
                {
                    nome: "MOVIES",
                    current: false
                },
                {
                    nome: "TV",
                    current: false
                },
                {
                    nome: "GAMES",
                    current: false
                },
                {
                    nome: "COLLECTIBLE",
                    current: false
                },
                {
                    nome: "VIDEOS",
                    current: false
                },
                {
                    nome: "FANS",
                    current: false
                },
                {
                    nome: "NEWS",
                    current: false
                },
                {
                    nome: "SHOP",
                    current: false
                }
            ]
        }
    }
    
        
    
}
</script>
<template>
   <header>
        <div class="cont">
            <div class="first-cont">
                <img src="/img/dc-logo.png" alt="logo">
            </div>
            <div class="second-cont">
                <ul>
                    <li v-for="(elem, index) in array">
                        <a href="#">{{elem.nome}}</a>
                    </li>
                     <!-- <li>
                        <a href="#">COMICS</a>
                    </li>
                    <li>
                        <a href="#">MOVIES</a>
                    </li>
                    <li>
                        <a href="#">TV</a>
                    </li>
                    <li>
                        <a href="#">GAMES</a>
                    </li>
                    <li>
                        <a href="#">COLLECTIBLE</a>
                    </li>
                    <li>
                        <a href="#">VIDEOS</a>
                    </li>
                    <li>
                        <a href="#">FANS</a>
                    </li>
                    <li>
                        <a href="#">NEWS</a>
                    </li>
                    <li>
                        <a href="#">SHOP</a>
                    </li> -->
                </ul>
            </div>
        </div>
   </header>
</template>
<style scoped lang="scss">

header{
height: 120px;
background-color: white;
    .cont{
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 80%;
        height: 100%;
        margin: 0 auto;
    }

    .second-cont{
    display: flex;
        ul {
            display: flex;
            align-items: center;
            height: 100%;
            li {
                list-style-type: none;
                margin: 0 10px;
                height: 100%;
                
                
            a {
                text-decoration: none;
                color: black;
                &:hover{
                    color: blue;
                    border-bottom: 2px solid blue
                }
                
            }
            }
        }
    };
}


</style>