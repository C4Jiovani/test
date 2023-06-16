<template>
    <div class="head">
        <div class="left"></div>
        <div class="img"><Compo></Compo></div>
    </div>
</template>

<script>
import Compo from './Compo.vue';
    export default({
        name: "laTete",
        data(){
            return {
                head: ["Home","Services","Our project","About Us"]
            }
        },
        components:{
            Compo
        }
    })
</script>
<style scoped>
*{
        top: 0;
        left: 0;
        padding: 0;
        right: 0;
}
    .head{
        width: 90%;
        height: 565px;
        background-color: #333;
        margin-left: 5%;
    }
    .left{
        width: 50%;
        height: 100%;
        background-image: url(../assets/logo.png);
        background-repeat: no-repeat;
        background-position: cover;
        align-items: center;
        background-position: 50% 50%;
    }
    .img{
        width: 48%;
        height: 98%;
        background-color: #41b883;
        margin-left: 51%;
        margin-top: -46%; 
    }
</style>