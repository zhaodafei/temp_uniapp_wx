<template>
  <view class="content">
    <view class="text-area">
      <text class="title">{{ title }}</text>
    </view>

    <view class="text-area">
      <text class="title" style="color: #ff6b81">{{ content }}</text>
    </view>
  </view>
</template>

<script setup>
import { ref } from "vue";
import { onLoad, onReady } from "@dcloudio/uni-app";

const title = ref("我的模块");
const content = ref("我的数据内容");
</script>

<style>
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.logo {
  height: 200rpx;
  width: 200rpx;
  margin-top: 200rpx;
  margin-left: auto;
  margin-right: auto;
  margin-bottom: 50rpx;
}

.text-area {
  display: flex;
  justify-content: center;
}

.title {
  font-size: 36rpx;
  color: #8f8f94;
}
</style>
