<script setup lang="ts">
import leftSideBar from './components/LeftSideBar.vue';


</script>

<template>
  <el-container>

    <leftSideBar></leftSideBar>
    <RouterView/>
  </el-container>

  <!-- <SqlPage></SqlPage> -->
</template>

<style>
.el-container {
  height: 100%;
}
</style>
