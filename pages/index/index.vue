<template>
	<view class="">
		<view class="flex font-lg text-white">
			<view class="flex flex-1 bg-success align-center justify-center">
				1
			</view>
			<view class="flex flex-1 bg-danger align-center justify-center">
				2
			</view>
		</view>
		<view class="flex justify-center align-center animated" hover-class="rubberBand">
			<view class="iconfont iconjinbi text-danger" style="font-size: 100rpx;">
				
			</view>
		</view>
		
	</view>
	
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		onNavigationBarSearchInputClicked(e) {
			console.log(e);
		},
		onNavigationBarButtonTap(e) {
			console.log(e);
		},
		methods: {

		}
	}
</script>

<style>
	
</style>
