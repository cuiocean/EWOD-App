<template>
	<view class="content">
		<view class="info">
			点击连接蓝牙设备
		</view>
		<view class="button">
			<u-button type="primary" :ripple="true">蓝牙设备</u-button>
		</view>
		<view class="info">
			文字说明设备名称,如何链接,等等
		</view>
	</view>
</template>

<script>
export default {
	data() {
		return {
			title: 'Hello'
		};
	},
	onLoad() {},
	methods: {}
};
</script>

<style>
.content {
	text-align: center;
	height: 400upx;
	margin-top: 200upx;
}
</style>
