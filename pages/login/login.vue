<template>
	<view class="main">
		<view class="logo">
			<image src="../../static/img/login/logo..png" mode=""></image>
		</view>
		<view class="content">
			<view class="input">
				<span class="icon1">
					<image src="../../static/img/login/艾特.png" mode=""></image>
				</span>
				<span class="info">
					请输入手机号/邮箱
				</span>
			</view>
			<view class="input">
				<span class="icon1">
					<image src="../../static/img/login/密码@2x.png" mode=""></image>
				</span>
				<span class="info">
					请输入密码
				</span>
				<span class="icon2">
					<image src="../../static/img/login/闭眼.png" mode=""></image>
				</span>
			</view>
			<view>
				<button class="btn">登录</button>
			</view>
			<view class="otherinfo">
				<span class="spl">海外手机号登录</span>
				<span class="spr">忘记密码</span>
			</view>
			<view class="zhuce">
				立即注册
			</view>
			<view class="disanfang">
				第三方软件登录
			</view>
			<view class="bottom-icon">
				<view class="icon3">
					<image src="../../static/img/login/qq.png" ></image>
				</view>
				<view class="icon3">
					<image src="../../static/img/login/微博.png" ></image>
				</view>
				<view class="icon3">
					<image src="../../static/img/login/微信.png" ></image>
				</view>
				
			</view>
		</view>
	</view>
</template>

<script>
</script>
<style scoped lang="scss">
	.main {
		width: 100%;
		height: 100%;
		background-color: #F1ECE7;
	}

	.logo {
		height: 336rpx;
		width: 100%;

		image {
			width: 212rpx;
			height: 212rpx;
			margin-top: 154rpx;
			margin-left: 270rpx;
		}
	}

	.content {
		width: 536rpx;
		height: 994rpx;
		// background-color: yellow;
		margin-top: 150rpx;
		margin-left: 108rpx;

		.input {
			width: 100%;
			height: 78rpx;
			margin-top: 36rpx;
			background-color: #E3DFDA;
			border-radius: 14rpx;
			position: relative;
			color: #C3C1BE;

			.icon1 {
				position: absolute;
				display: inline-block;
				width: 32rpx;
				height: 32rpx;
				left: 24rpx;
				top: 22rpx;
				bottom: 24rpx;

				image {
					width: 100%;
					height: 100%;
				}
			}

			.icon2 {
				position: absolute;
				display: inline-block;
				width: 34rpx;
				height: 22rpx;
				left: 462.7rpx;
				top: 20rpx;

				image {
					width: 100%;
					height: 100%;
				}
			}

			.info {
				position: absolute;
				display: inline-block;
				font-size: 24rpx;
				left: 72rpx;
				top: 28rpx;
				letter-spacing: 1.71rpx;
			}
		}

		.btn {
			margin-top: 48rpx;
			background-color: #354E44;
			border-radius: 14rpx;
			text-align: center;
			color: #FFFFFF;
			font-size: 30rpx;
		}

		.otherinfo {
			margin-top: 22rpx;
			font-size: 24rpx;
			color: #A5A5A5;
			letter-spacing: 1.71rpx;

			.spr {
				margin-left: 251rpx;
			}
		}

		.zhuce {
			margin-top: 239rpx;
			text-align: center;
			font-size: 40rpx;
			color: #354E44;
			letter-spacing: 2.86rpx;
		}
		.disanfang{
			margin-top: 26rpx;
			font-size: 24rpx;
			text-align: center;
			color: #A5A5A5;
			letter-spacing: 1.71rpx;
		}
		.bottom-icon{
			margin-top: 69rpx;
			margin-left: 72rpx;
			.icon3{
				width: 64rpx;
				height: 64rpx;
				margin-left: 52rpx;
				display: inline-block;
				image{
					width: 100%;
					height: 100%;
				}
			}
		}
	}
</style>
