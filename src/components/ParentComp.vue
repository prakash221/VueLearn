<template>
    <div class="parent-comp">
    <TestifElse/>
    <HomePage data="Passing Data from App" msg="Pass 2 or more data from App.vue"/>
    <LoopLearn/>
    </div>
</template>
<script>
import TestifElse from './ifelsewithBtn'
import HomePage from './Home'
import LoopLearn from './ForLoop'
export default {
    name:"ParentComp",
    components:{
        TestifElse,
        HomePage,
        LoopLearn
    }
}
</script>
<style>
.parent-comp{
    background-color: beige;

}
</style>