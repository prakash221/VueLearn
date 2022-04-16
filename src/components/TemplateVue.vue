<template>
    <div >
        <span v-html="header"></span>
       
        <!-- v-template -->
        
        <h2 v-once>{{name}}</h2>
        <h2>{{name}}</h2>

        <button v-bind:disabled="btnDisable" v-on:click="hellometh">Click me</button>

        <p>Arithemetic Operation in double curly</p>
        <p>{{1+100*2}}</p>

        <h3>{{ok?"Yes":"No"}}</h3>
    </div>
</template>
<script>
export default {
    name:"TemplateL",
    data(){
        return{
            name:"Peter Sharma",
            ok:true,
            header:"<h1>Template Example</h1>",
            btnDisable: true
        }
    },
    methods:{
        hellometh(){
            this.ok = !this.ok
            this.name = "Prakash Sharma"
        }
    }
}
</script>
<style>
.home{
    background-color: gray;
}
</style>