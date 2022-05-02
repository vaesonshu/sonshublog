<template>
  <el-menu
    :default-active="activeIndex"
    class="el-menu-demo"
    mode="horizontal"
    @select="handleSelect"
  >
    <el-menu-item index="1">模块一</el-menu-item>
    <el-menu-item index="2">模块二</el-menu-item>
    <el-menu-item index="3">模块三</el-menu-item>
    <el-menu-item index="4">模块四</el-menu-item>
    <el-menu-item index="4">模块五</el-menu-item>
    <el-menu-item index="4">模块六</el-menu-item>
  </el-menu>
</template>

<script lang="ts" setup>
import { ref } from 'vue'

const activeIndex = ref('1')
const activeIndex2 = ref('1')
const handleSelect = (key: string, keyPath: string[]) => {
  console.log(key, keyPath)
}
</script>

<style lang="less" scoped></style>
