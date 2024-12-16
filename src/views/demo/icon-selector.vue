<!-- 图标选择器示例 -->
<script setup lang="ts">
const iconName = ref("el-icon-edit");
</script>

<template>
  <div class="app-container">
    <icon-select v-model="iconName" />
  </div>
</template>
