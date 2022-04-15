<template>
    <div class="ifelse">
        <h1 v-if="show">Conditional Rendering in View</h1>
        <!-- <h1 v-else>else part of the conditional</h1> -->
        <button v-on:click="display">toogle if</button>
    </div>
</template>
<script>
export default {
    name:"TestifElse",
    props:{
        data:String,
        msg:String
    },
    data(){
        return{
            show:false
        }
    },
    methods:{
        display(){
            this.show = !this.show
        }
    }
}
</script>
<style>
.ifelse{
    background-color: rgb(255, 164, 164);
}
</style>