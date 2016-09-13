<!doctype html>
<html>
<head>
<meta charset="utf-8">
<title>倒计时</title>
<script src="http://libs.baidu.com/jquery/1.10.2/jquery.min.js"></script>
</head>

<body>
<script type="text/javascript">
var num = 60;
function daojishi(obj){
	
	if(num==0){
		obj.removeAttribute("disabled");
		obj.value="免费获取验证码";
		num = 60;
	}else{
		obj.setAttribute("disabled",true);
		obj.value="重新发送("+num+")";
		num--;
	}
	
	
	setTimeout(function(){
		daojishi(obj);	
	},1000);	
}
</script>
<input type="button" id="btn" value="免费获取验证码" onclick="daojishi(this);" /> 
</body>
</html>
