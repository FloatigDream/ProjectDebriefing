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
					<text class="index-item-rightBox-lastDayBox-text">
						最后汇报时间:21年8月5日
					</text>
				</view>
				<view class="index-item-rightBox-numBox">
					<text class="index-item-rightBox-numBox-text">
						10个汇报
					</text>
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
	.list {
		list-style: none;
	}

	.index-item {
		display: flex;
		justify-content: space-between;
		border: 1rpx solid #CDCDCD;
	}

	.index-item-leftBox {
		padding: 10rpx;
		width: 60%;
	}

	.index-item-rightBox {
		padding: 10rpx;
		width: 40%;
	}
</style>