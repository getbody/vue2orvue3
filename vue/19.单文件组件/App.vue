<template>
    <div>
        <School/>
        <Sdutent/>
    </div>
</template>

<script>
// 引入组件
import School from './School'
import Sdutent from './Sdutent'

export default {
    name:'App',
    components:{
        School,
        Sdutent
    }
};
</script>

<style>
</style>