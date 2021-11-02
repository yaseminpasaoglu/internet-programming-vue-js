<template>
    <button v-on:click="hello">click here</button>
</template>

<script>    
    export default{

        name:'home',
        props :{
            data: String,
            msg: String
        },methods:{
            hello()
            {
                alert("Hello World")
            }
        }
    }

</script>

<style >
button{
    outline: none;
    border-style: solid;
    background: sandybrown;
    position: relative;
}
</style>