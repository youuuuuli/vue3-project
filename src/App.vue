<script lang="ts" setup>
import { ref } from 'vue'
import zhCn from 'element-plus/dist/locale/zh-cn.mjs'

const locale = ref(zhCn)
</script>

<template>
  <el-config-provider :locale="locale">
    <el-container>
      <el-header> Header </el-header>
      <el-main> Main </el-main>
    </el-container>
  </el-config-provider>
</template>

<style scoped></style>
