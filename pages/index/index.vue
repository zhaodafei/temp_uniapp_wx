<template>
	<view class="content">
		<image class="logo" src="/static/logo.jpg"></image>
		<view class="text-area">
			<text class="title">{{title}}</text>
		</view>

    <view class="text-area">
      <text class="title" style="color: #ff6b81">{{content}}</text>
    </view>
	</view>
</template>

<script setup>
import {ref} from 'vue'
import {onLoad, onReady} from '@dcloudio/uni-app'

const title = ref('Hello')
const content = ref('uniapp开发小程序启动')

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
