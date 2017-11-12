<template>
	<div class="left-nav">
		<ul>
			<li>
				<i class="icon iconfont icon-31goumaichongzhi"></i>
				<div>收银</div>
			</li>
			<li>
				<i class="iconfont icon-dianpu"></i>
				<div>店铺</div>
			</li>
			<li>
				<i class="iconfont icon-hanbao"></i>
				<div>商品</div>
			</li>
			<li>
				<i class="iconfont icon-31huiyuanqia"></i>
				<div>会员</div>
			</li>
			<li>
				<i class="iconfont icon-31goumaichongzhi"></i>
				<div>统计</div>
			</li>
			<li>
				<i class="iconfont icon-gongnengjianyi"></i>
				<div>设置</div>
			</li>
		</ul>
	</div>
</template>

<script>
	export default {
		name:'leftNav',
		data(){
			return{
				
			}
		}
	}
</script>

<style>
	.left-nav{
		float: left;
		width: 5%;
		height: 100%;
		color: #fff;
		font-size: 10px;
		background-color: #1D8CE0;
	}
	.iconfont{
		font-size: 24px;
	}
	.left-nav ul{
		padding: 0;
		margin: 0;
	}
	.left-nav li{
		list-style: none;
		text-align: center;
		border-bottom: 1px solid #20a0ff;
		padding: 10px;
	}
</style>