<template>
     <el-row :gutter="0" class="m-header">
        <el-col :span="5">
            <geo/>
        </el-col>
        <el-col :span="5">
            <user></user>
        </el-col>
        <el-col :span="14">
            <nav-bar></nav-bar>
        </el-col>
    </el-row>
</template>

<script>
import Geo from './geo.vue'
import User from './user.vue'
import navBar from './nav.vue'
export default {
    components:{
        Geo,
        User,
        navBar
    }

}
</script>

<style lang="scss">
    @import "@/assets/css/public/layout.scss";
     @import "@/assets/css/public/header/index.scss";
</style>
