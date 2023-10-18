<template>

	<view class="pageIndex">
		<view class="bar">

		</view>
		<view class="header">
			<view class="contentMain">

				<view class="status_bar">

					<text>
						<i class="iconfont">&#xe62d;</i> 离离原上普大学城西校区<text class="sub_bar">◢</text>
					</text>


				</view>
			</view>


		</view>
		<view class="headerButtom">

			<view class="bcg">


				<view class="top">
					<view class="search">
						<view class="left">
							<i class="iconfont">&#xe631;</i>
							<text class="sx1">|</text>
						</view>
						<view class="right">
							<i class="iconfont">&#xe7da;</i>
							<text>想吃什么</text>
						</view>
					</view>

				</view>
				<view class="bottom">
					<swiper :indicator-dots="true" :autoplay="true" :interval="7000" :duration="1000" class="swiper"
						easing-function="easeOutCubic" indicator-active-color="#ffffff" circular="true">
						<swiper-item>
							<view class="swiper-item1">

							</view>
						</swiper-item>
						<swiper-item>
							<view class="swiper-item2">

							</view>
						</swiper-item>
						<swiper-item>
							<view class="swiper-item3">

							</view>
						</swiper-item>
					</swiper>
				</view>
			</view>
		</view>
		<view class="middle">
			<view class="content">
				<ul>
					<li class="icon1">
						<image src="../../static/image/eatwest.jpg" mode=""></image>
						<text>一食堂一楼</text>

					</li>
					<li>
						<image src="../../static/image/huo1.jpg" mode=""></image>
						<text>一食堂二楼</text>
					</li>
					<li>
						<image src="../../static/image/icecream.jpg" mode=""></image>
						<text>商业街</text>
					</li>
					<li>
						<image src="../../static/image/eatwest.jpg" mode=""></image>
						<text>紫金红广场</text>
					</li>
					<li>
						<image src="../../static/image/eatwest.jpg" mode=""></image>
						<text>生活超市</text>
					</li>
					<li>
						<image src="../../static/image/eatwest.jpg" mode=""></image>
					</li>
					<li>
						<image src="../../static/image/eatwest.jpg" mode=""></image>
					</li>

				</ul>

			</view>

		</view>
		<view class="bottom2">
			<view class="content">
				<view class="listbody">

				</view>
			</view>
		</view>
	</view>


</template>

<script>
	export default {
		data() {
			return {

			}
		},

		onLoad: function() {

		},
		methods: {

		}
	}
</script>

<style lang="less">
	@font-face {
		font-family: 'iconfont';
		/* Project id 4237618 */
		src: url('//at.alicdn.com/t/c/font_4237618_xdpwldxu518.woff2?t=1693881989571') format('woff2'),
			url('//at.alicdn.com/t/c/font_4237618_xdpwldxu518.woff?t=1693881989571') format('woff'),
			url('//at.alicdn.com/t/c/font_4237618_xdpwldxu518.ttf?t=1693881989571') format('truetype');
	}

	@font-face {
		font-family: 'iconfont';
		/* Project id 4238394 */
		src: url('//at.alicdn.com/t/c/font_4238394_ykwqwvodgc.woff2?t=1693901806992') format('woff2'),
			url('//at.alicdn.com/t/c/font_4238394_ykwqwvodgc.woff?t=1693901806992') format('woff'),
			url('//at.alicdn.com/t/c/font_4238394_ykwqwvodgc.ttf?t=1693901806992') format('truetype');
	}

	/* 字体图标引用阿里 */
	@font-face {
		font-family: 'iconfont';
		/* Project id 4238394 */
		src: url('//at.alicdn.com/t/c/font_4238394_nreshxxy8s.woff2?t=1693904189550') format('woff2'),
			url('//at.alicdn.com/t/c/font_4238394_nreshxxy8s.woff?t=1693904189550') format('woff'),
			url('//at.alicdn.com/t/c/font_4238394_nreshxxy8s.ttf?t=1693904189550') format('truetype');
	}

	.pageIndex {

		font-size: 0;


		.bar {
			height: var(--status-bar-height);
			width: 100%;
			background-color: #F47119;
		}

		.header {

			height: 90rpx;
			width: 100%;
			background-color: #F47119;

			.contentMain {
				margin: 0 30rpx;

				.status_bar {


					color: #FFFFFF;
					font-weight: 900;
					font-size: 30rpx;



					>text {
						display: inline-block;
						width: 750rpx;
						height: 40rpx;
						margin-top: 20rpx;

						.iconfont {
							font-family: "iconfont" !important;
							font-size: 16px;
							font-style: normal;
							-webkit-font-smoothing: antialiased;
							-webkit-text-stroke-width: 0.2px;
							-moz-osx-font-smoothing: grayscale;
							margin-right: 10rpx;
						}

						.sub_bar {
							margin-top: 20rpx;
							margin-left: 15rpx;
							font-size: 20rpx;
							line-height: 40rpx;
							vertical-align: -5rpx;


						}




					}
				}
			}

		}

		.headerButtom {

			width: 100%;
			height: 460rpx;
			position: relative;
			background-color: #F3F3F3;


			.bcg {
				position: absolute;

				height: 85%;
				width: 120%;
				background-color: #F47119;
				border-bottom-left-radius: 0%;
				border-bottom-right-radius: 90%;
				display: inline-block;



				.top {
					margin: 0 30rpx;
					padding-top: 20rpx;





					.search {

						border: 2rpx solid #fff;
						width: 82%;
						height: 80rpx;
						background-color: #FFFFFF;
						border-radius: 40rpx;


						.left {
							margin-top: 10rpx;
							margin-left: 30rpx;
							float: left;


							.iconfont {
								font-family: "iconfont" !important;
								font-size: 60rpx;
								color: #F47119;
								font-weight: 500;
								font-style: normal;
								-webkit-font-smoothing: antialiased;
								-webkit-text-stroke-width: 0.2px;
								-moz-osx-font-smoothing: grayscale;
								margin-right: 14rpx;
								align-items: center;

							}

							.sx1 {
								line-height: 20rpx;
								vertical-align: 10rpx;
								align-items: center;
								font-size: 40rpx;
								color: #BFBFBF;

							}
						}

						.right {
							float: left;
							margin-left: 18rpx;
							margin-top: 18rpx;



							.iconfont {
								font-family: "iconfont" !important;
								font-size: 40rpx;
								color: #999999;
								font-weight: 500;
								font-style: normal;
								-webkit-font-smoothing: antialiased;
								-webkit-text-stroke-width: 0.2px;
								-moz-osx-font-smoothing: grayscale;
								margin-right: 10rpx;
								align-items: center;
								margin-right: 15rpx;
							}

							>text {
								color: #999999;
								line-height: 20rpx;
								vertical-align: 2rpx;
								font-size: 24rpx
							}

						}
					}
				}

				.bottom {
					margin: 0 30rpx;



					.swiper {
						box-shadow: 0px 5px 5px #bebebe;
						overflow: hidden;
						margin-top: 20rpx;
						height: 310rpx;
						width: 82%;
						border-radius: 20rpx;
						font-size: 0;




						.swiper-item1 {
							background-image: url(../../static/image/swiper1.png);
							width: 100%;
							height: 100%;
							background-repeat: no-repeat;
							background-size: cover;


						}

						.swiper-item2 {
							background-image: url(../../static/image/swiper2.png);
							width: 100%;
							height: 100%;
							background-repeat: no-repeat;
							background-size: cover;
						}

						.swiper-item3 {
							background-image: url(../../static/image/swiper3.png);
							width: 100%;
							height: 100%;
							background-repeat: no-repeat;
							background-size: cover;
						}
					}
				}
			}

		}

		.middle {
			width: 100%;
			display: inline-block;
			background-color: #F3F3F3;


			.content {
				margin: 0 30rpx;


				height: 90%;

				ul {

					height: 40rpx;
					font-size: 24rpx;
					padding-left: 0;
					list-style-type: none;


					li {
						float: left;
						margin-right: 27rpx;
						margin-top: 15px;
						width: 60px;
						height: 60px;

						text-align: center;

						&:nth-child(0n+5) {
							margin-right: 0;
						}


						image {
							width: 80rpx;
							height: 80rpx;
							float: left;
							border-radius: 50%;
							margin: 0 2px;
						}

						text {

							font-size: 12px;
							float: left;
							margin-top: 5px;


						}

					}
				}


			}
		}

		.bottom2 {
			width: 100%;

			background-color: #F3F3F3;
			height: 500px;

			.content {
				margin: 0 30rpx;


				height: 100%;

				.listbody {
					background-color: #FFFFFF;
					width: 100%;
					height: 90%;
					border-radius: 15px;
				}
			}
		}
	}
</style>