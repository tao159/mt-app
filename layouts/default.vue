<template>
  <el-container class="layout-default">
    <el-header>
      <my-header></my-header>
    </el-header>
    <el-main>
      <nuxt/>
    </el-main>
    <el-footer height="100%">
       <Myfooter></Myfooter>
    </el-footer>
  </el-container>
</template>

<script>
import MyHeader from '@/components/public/header/index.vue'
import Myfooter from '@/components/public/footer/index.vue'
export default {
  components:{
    MyHeader,
    Myfooter
  }
}
</script>


<style>

</style>
