<template>
	<div class="header">
		<div class="left">
			<i class="iconfont icon-fanhui"></i>
		</div>
		<div class="middle">
			<i class="iconfont icon-sousuo"></i>
			请随意输入一些内容
		</div>
		<div class="right">
			城市
			<i class="iconfont icon-arrow-down-filling"></i>
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