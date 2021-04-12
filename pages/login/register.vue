<template>
	<view class="main">
		<view class="top">
			<view class="title">
				注册
			</view>
		</view>
		<view class="content">
			<view class="input1">
				请输入手机号/邮箱
			</view>
			<view class="input2">
				获取短信验证码
			</view>
			<view class="beizhu">
				完成注册即代表你同意用户协议和隐私政策
			</view>
			<view class="gologin">
				已有账号 去登录
			</view>
		</view>
		
	</view>
</template>

<script>
</script>

<style lang="scss" scoped>
	.main {
		width: 100%;
		height: 100%;
		background-color: #F1ECE7;
		.top {
			height: 300rpx;
			width: 100%;
			position: relative;
			font-size: 60rpx;
			color: #354E44;
			letter-spacing: 4.29rpx;
			.title {
				position: absolute;
				left: 110rpx;
				top: 138rpx;
			}
		}
		.content{
			clear: both;
			margin-top: 38rpx;
			margin-left: 108rpx;
			width: 536rpx;
			height: 1324rpx;
			.input1{
				width: 100%;
				height: 98rpx;
				text-align: center;
				line-height: 98rpx;
				margin-top: 48rpx;
				font-size: 30rpx;
				border-radius: 14rpx;
				color: #FFFFFF;
				letter-spacing: 2.14rpx;
				background-color: #354E44;
			}
			.input2{
				width: 100%;
				height: 98rpx;
				text-align: center;
				line-height: 98rpx;
				margin-top: 48rpx;
				border-radius: 14rpx;
				font-size: 30rpx;
				color: #FFFFFF;
				letter-spacing: 2.14rpx;
				background-color: #354E44;
			}
			.beizhu{
				margin-top: 22rpx;
				font-size: 24rpx;
				color: #A5A5A5;
				letter-spacing: 1.71rpx;
			}
			.gologin{
				text-align: center;
				margin-top: 215rpx;
				font-size: 32rpx;
				color: #354E44;
				letter-spacing: 2.29rpx;
			}
		}
		

	}
</style>
