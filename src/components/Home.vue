<template>
    <div>
        <h1>First Component</h1>
        <h2>{{data}}</h2>
        <h3>{{msg}}</h3>
    </div>
</template>
<script>
export default {
    name:"HomePage",
    props:{
        data:String,
        msg:String
    }
}
</script>