<template>
	<div class="header">
		<div class="left">
			<span class="iconfont">&#xe624;</span>
		</div>
		<div class="middle">
			<span class="iconfont">&#xe632;</span>
			请随意输入一些内容
		</div>
		<div class="right">
			城市
			<span class="iconfont">&#xe688;</span>
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