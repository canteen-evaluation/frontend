<template>
  <view class="profile-container">
    <view class="title">我的页面</view>
    <view class="content">
      <text>这里是个人信息区域</text>
    </view>
  </view>
</template>

<script setup lang="ts">
import { onMounted } from 'vue';

onMounted(() => {
  console.log('我的页面已加载');
});
</script>

<style lang="scss">
.profile-container {
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