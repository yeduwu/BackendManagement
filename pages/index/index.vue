<template>
	<view class="content">
		<view class="loginBox">
			<view class="com_tit">密码登录</view>
			<view class="com_txt"></view>
			<view>
				<input type="text" placeholder="请输入账号"/>
			</view>
			<view>
				<input type="safe-password" password="" maxlength="16" placeholder="请输入密码">
			</view>
			<navigator class="btnLogin">登录</navigator>
		</view>
	</view>
</template>

<script>
	
</script>

<style>
.com_tit{
	font-size: 30px;
	font-weight: 300;
	color: #000;
	text-align: center;
}
.com_txt{
	font-size: 22px;
	font-weight: 300;
	color: #000;
	text-align: center;
}
.loginBox{
	width: 100%;
	padding-top: 50px;
	overflow: hidden;
}
.loginBox input{
	width: 250px;
	height: 20px;
	border: 1px solid #ccc;
	margin: 15px auto;
	border-radius: 5px;
	padding: 10px 0 10px 16px;
	font-size: 16px;
	
}
.btnLogin{
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
