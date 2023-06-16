<template>
    
    <div class="right">
        <h2>Mes Premiers Composants en vueJs</h2>
        <div>
            <Layouts></Layouts>
        </div>
    </div>

</template>

<script>
import Layouts from './Layouts.vue';
    export default({
        name: "leCompo",
        data(){
            return{
                
            }
        },
        components:{
            Layouts
        }
    })
</script>
<style scoped>

*{
    margin: 0;
    padding: 0;
    left: 0;
    top: 0;
    right: 0;
}
.right{
    font-family: fantasy;
    text-align: center;
    color: #5e3548;
}
</style>