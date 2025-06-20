<template>
  <view class="content">
    <view class="text-area">
      <text class="title">{{ title }}ssssssssssss </text>
    </view>

    <view class="text-area">
      <text class="title" style="color: #ff6b81">{{ content }}</text>
    </view>
  </view>
</template>

<script setup>
import { ref } from "vue";
import { onLoad, onReady } from "@dcloudio/uni-app";

const title = ref("信息查看");
const content = ref("信息查看");
</script>

<style>
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
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
