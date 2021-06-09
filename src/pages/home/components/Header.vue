<template>
	<div class="header">
		<div class="left">
			<span class="iconfont icon-fanhui"></span>
		</div>
		<div class="middle">
			<span class="iconfont icon-sousuo"></span>
			请随意输入一些内容
		</div>s
		<div class="right">
			城市
			<span class="iconfont icon-arrow-down-filling"></span>
		</div>
	</div>
</template>

<script>
export default {
	name: 'Header',
}
</script>

<style scoped>
.header {
	height: 50px;
	display: flex;
	align-items: center;
	background: #00bcf4;
	color: #fff;
}
.header .left {
	padding: 0 10px;
}
.header .middle {
	flex: 1;
	background: #fff;
	border-radius: 3px;
	padding: 5px;
	color: #aaa;
}
.header .right {
	padding: 0 20px;
}  
</style>