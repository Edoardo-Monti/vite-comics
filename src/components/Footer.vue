<script>
import FirstFooter from './FirstFooter.vue';
import SecondFooter from './SecondFooter.vue';
import ThirdFooter from './ThirdFooter.vue';


export default{
    name: "Footer",
    components: { FirstFooter, SecondFooter, ThirdFooter }
}

</script>
<template>
    <div>
        <FirstFooter/>
        <SecondFooter/>
        <ThirdFooter/>
    </div>

</template>
<style>

</style>