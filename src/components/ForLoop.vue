<template>
    <div>
        <h1>For Loop</h1>
        <table border="2px">
            <tr>
                <th>Id</th>
                <th>Name</th>
                <th>Email</th>
            </tr>
            <tr v-for="user in users" :key="user.id">
                <th>{{user.id}}</th>
                <th>{{user.name}}</th>
                <th>{{user.email}}</th>
            </tr>
            
        </table>
       
    </div>
</template>
<script>
export default {
    name:"LoopLearn",
    props:{
        data:String
    },
    data(){
        return {
            users:[
                {id:1,name:"prakash",email:"prakash.psc221@gmail.com"},
                {id:2,name:"saraswati",email:"saraswati@gmail.com"},
                {id:3,name:"dipesh",email:"dipesh@gmail.com"},
                {id:4,name:"iram",email:"iram@gmail.com"}
            ]
        };
    }
};
</script>