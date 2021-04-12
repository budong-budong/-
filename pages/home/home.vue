<template>
	<view class="">
		<view class="top">
			<view class="top-title">
				<view class="message">
					<image src="../../static/img/home/消息.png" mode=""></image>
				</view>
				<view class="tuijian">
					<span>推荐</span>
					<span>品牌</span>
				</view>
				<view class="search">
					<image src="../../static/img/home/消息.png" mode=""></image>
				</view>
				<view class="buycar">
					<image src="../../static/img/home/消息.png" mode=""></image>
				</view>
			</view>
			<image src="../../static/img/home/banner1.png" mode=""></image>
			
		</view>
		<view class="title">
			品类推荐
		</view>
		<view class="type">
			
		</view>
		<view class="title">
			特色优选
		</view>
		<view class="special">
			
		</view>
	</view>
	
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style lang="scss" scoped>
	.top{
		width: 100%;
		height: 426rpx;
		// background-color: yellow;
		image{
			z-index: -1;
			width: 100%;
			height: 100%;
			margin-top: -45rpx;
		}
		.top-title{
			width: 100%;
			height:45rpx;
			z-index: 999;
			.message{
				display: inline-block;
				width: 42rpx;
				height: 42rpx;
				margin-left: 30rpx;
				image{
					width: 100%;
					height: 100%;
				}
			}
			.search{
				display: inline-block;
				width: 42rpx;
				height: 42rpx;
				margin-left: 151rpx;
				image{
					width: 100%;
					height: 100%;
				}
			}
			.buycar{
				display: inline-block;
				width: 42rpx;
				height: 42rpx;
				margin-left: 36rpx;
				image{
					width: 100%;
					height: 100%;
				}
			}
			.tuijian{
				display: inline-block;
				margin-left: 188rpx;
				span{
					margin-left: 30rpx;
					font-size: 32rpx;
					color: #FFFFFF;
					letter-spacing: 2.29rpx;
				}
			}
			
		}
	}
	.title{
		width: 100%;
		height: 40rpx;
		background-color: skyblue;
		
	}
	.type{
		width: 100%;
		height:297rpx;
		background-color: green;
	}
	.special{
		width: 100%;
		height:353rpx;
		background-color: pink;
	}

</style>
