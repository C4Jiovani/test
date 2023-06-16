<template>
    <p>{{ lo }}</p>
</template>

<script>
    export default({
        name: "leLayouts",
        data(){
            return{
                lo: "Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam, quas!"
            }
        }
    })
</script>

<style>
    p{
        width: 50%;
        border: black solid 1px;
        background-color: #35495e;
        text-align: center;
    }
</style>