<template>
	<view class="index-body">
		<view class="index-item">
			<view class="index-item-leftBox">
				<view class="index-item-leftBox-dayBox">
					<text class="index-item-leftBox-dayBox-text">
						2022年12月15日
					</text>
				</view>
				
				<view class="index-item-leftBox-titleBox ">
					<text class="index-item-leftBox-titleBox-text">
						项目一项目一项目一项目一项目一项目一项目一项目一项目一
					</text>
				</view>
			</view>
			
			<view class="index-item-rightBox">
				<view class="index-item-rightBox-lastDayBox">
					最后汇报时间:21年8月5日
				</view>
				<view class="index-item-rightBox-numBox">
					10个汇报
				</view>
			</view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>	
	.list{
		list-style: none;
		font-size: 20rpx;
	}
	
	.index-item{
		display: flex;
		justify-content: space-between;
	}
</style>