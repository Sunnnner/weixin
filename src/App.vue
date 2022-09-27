<template>
	<div class="card content-box">
		<iframe src="https://wx.qq.com/" frameborder="0" class="full-iframe"></iframe>
	</div>
</template>

<script setup lang="ts" name="embedded"></script>

<style scoped lang="scss">
.full-iframe {
	width: 100%;
	height: 100%;
}
// * card 卡片样式
.card {
	box-sizing: border-box;
	padding: 20px;
	overflow-x: hidden;
	background-color: var(--el-fill-color-blank);
	border: 1px solid var(--el-border-color-light);
	border-radius: 4px;
	box-shadow: 0 0 12px rgb(0 0 0 / 5%);
}

// * content-box (常用内容盒子)
.content-box {
	display: flex;
	flex-direction: column;
	align-items: center;
	height: 100%;
	.text {
		margin: 20px 0 30px;
		font-size: 23px;
		font-weight: bold;
		color: rgb(88 88 88);
	}
	.el-descriptions {
		width: 100%;
		padding: 40px 0 0;
		.el-descriptions__title {
			font-size: 18px;
		}
		.el-descriptions__label {
			width: 200px;
		}
	}
}

</style>
