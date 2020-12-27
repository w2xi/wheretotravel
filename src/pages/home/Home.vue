<template>
	<div>
		<div class="home">Home</div>
		<router-link to="/list" class="home">List</router-link>
	</div>
</template>

<script>
export default {
	name: 'Home',
}
</script>

<style>
.home {
	padding: 20px 40px;
	background-color: #f1a166;
	border: 1px solid #f0cc12;
	font-size: 40px;
}
</style>