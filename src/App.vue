<!-- 定义JS：控制模板部分的数据和行为 -->
<script setup>
import { ref } from 'vue';
import EmpList from "./views/EmpList.vue";

// 声明响应式数据
const message = ref('hello vue3');
</script>

<!-- 模板部分：控制的是页面的结构（html） -->
<template>
    <EmpList></EmpList>
</template>

<!-- 当前组件的css样式 -->
<style scoped>
</style>
