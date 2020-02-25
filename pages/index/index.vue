<template>
	<div id="indexPage">
		<div class="header">
			<image src="../../static/img/logo.png" alt="" class="logo">
			<div class="searchArea">
				<i class="iconfont icon-search1"></i>
				<input type="text" placeholder="请输入关键字" placeholder-class="inputholder">
			</div>
			<button>登录</button>
		</div>
	</div>
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
		methods: {

		}
	}
</script>

<style lang="stylus">
	#indexPage
		.header
			display flex
			width 100%
			height 60upx
			padding 10upx 0
			.logo
				width 140upx
				height 40upx
				margin 10upx 26upx 0 30upx
			.searchArea
				height 60upx
				width 346upx
				padding-left: 60upx;
				position relative
				background-color #F8F8F8
				border-radius 7upx
				.iconfont
					width 60upx
					height 60upx
					font-size 40upx
					position absolute
					top 4upx
					left 10upx
					color #999999
				input
					border-radius 10upx
					height 60upx
					width 390upx
				.inputholder
					font-size 24upx
					color #C0C0C0
			button
				width 120upx
				height 60upx
				line-height 54upx
				font-size 26upx
				margin 0 30upx 0 20upx
				border-radius 7px
				boder none
				color #F8F8F8
				background-color #aaaaff
				&:after		
					border none
</style>
