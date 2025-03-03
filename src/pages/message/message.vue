<template>
  <view class="message-container">
    <view class="title">消息页面</view>
    <view class="content">
      <text>这里是消息内容区域</text>
    </view>
  </view>
</template>

<script setup lang="ts">
import { onMounted } from 'vue';

onMounted(() => {
  console.log('消息页面已加载');
});
</script>

<style lang="scss">
.message-container {
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