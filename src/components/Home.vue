<template>
    <div>
        <h1>First Component</h1>
        <h2>{{data}}</h2>
        <h3>{{msg}}</h3>
        <button v-on:mouseover="hello('data')">Call Function</button>
    </div>
</template>
<script>
export default {
    name:"HomePage",
    props:{
        data:String,
        msg:String
    },
    methods:{
        hello(item){
            console.warn(item)
        }
    }
}
</script>