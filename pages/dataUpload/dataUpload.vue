<template>
	<view>
		<view class="inputBox">
			<view class="com_txt">名称: </view>
			<input type="text">
		</view>	
		<view class="inputBox">
			<view class="com_txt">价格: </view>
			<input type="number">
		</view>	
		<view class="inputBox">
			<view class="com_txt">花龄: </view>
			<input type="number">
		</view>	
		<view class="inputBox">
			<view class="com_txt">习性: </view>
			<input type="text">
		</view>	
		<view class="inputBox">
			<view class="com_txt">方法: </view>
			<input type="text">
		</view>	
		<view class="inputBox last-child">
			<view class="com_txt">选择图片上传:</view>
			<input type="text">
		</view>
		<navigator class="btnSubmit">提交</navigator>
	</view>
</template>

<script setup>
	
</script>

<style>
.com_txt{
	font-size: 22px;
	font-weight: 300;
	color: #000;
	text-align: center;
	display: inline-block;
	vertical-align: text-bottom;
	margin-right: 4px;
}
.inputBox{
	width: 100%;
	height: 80px;
	line-height: 80px;
	padding-left: 22px;
	overflow: hidden;
}  
.inputBox.last-child{
	height: 200px;
}
input{
	display: inline-block;
	width: 250px;
	height: 20px;
	border: 1px solid #ccc;
	margin: 15px auto;
	border-radius: 5px;
	padding: 10px 0 10px 16px;
	font-size: 16px;
	
}

.btnSubmit{
	width: 132px;
	height: 36px;
	line-height: 36px;
	border-radius: 5px;
	text-align: center;
	font-size: 16px;
	background: #09F;
	color: #fff;
	margin: 0 auto;
}
</style>
