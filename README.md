# baiduCollege
answer(1)
```<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="Generator" content="EditPlus®">
  <meta name="Author" content="">
  <meta name="Keywords" content="">
  <meta name="Description" content="">
  <title>Document</title>
  
 </head>
 <body>
  <label>请输入你的姓名：<input type="text"class="text"/></label>
	<input type="button"class="btn" value="提交"onclick="func()">
	<div id="" class="">
		您输入的值是：<span class="span">暂无输入</span>
	</div>
	<script type="text/javascript">
	func(){
		var m = document.getElementsByClass("text")[0].value;
		document.getElementsByClass("span")[0].innerText = m;
	}
  </script>
 </body>
</html>

