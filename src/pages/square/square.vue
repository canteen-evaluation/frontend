<template>
  <view class="square-container">
    <view class="title">广场页面</view>
    <view class="content">
      <text>这里是广场内容区域</text>
    </view>
  </view>
</template>

<script setup lang="ts">
import { onMounted } from 'vue';

onMounted(() => {
  console.log('广场页面已加载');
});
</script>

<style lang="scss">
.square-container {
  padding: 20px;
  
  .title {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 20px;
    text-align: center;
  }
  
  .content {
    background-color: #f8f8f8;
    padding: 15px;
    border-radius: 8px;
    text-align: center;
  }
}
</style> 