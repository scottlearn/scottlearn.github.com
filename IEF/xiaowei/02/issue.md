* 设置了.active的颜色，但是a.active继承父级属性。
```
<nav class="navbar clearfix">
	<ul>
		<li><a class="active" href="#">导航链接四</a></li>
		<li><a href="#">导航链接三</a></li>
		<li><a href="#">导航链接二</a></li>
		<li><a href="#">导航链接一</a></li>
	</ul>
</nav>
```
以下代码成功
```
.navbar a{
	color: #fff;
}
.navbar .active{
	color: #9F9E9E;
}
```
以下代码不成功
```
.navbar a{
	color: #fff;
}
.active{
	color: #9F9E9E;
}
```
突击知识点：css继承。

* 设置img的尺寸是如何保证宽高比[对宽高同时使用相等百分比赋值]？什么时候用img什么时候用bg？

* 不用float，如何设置css能使dt和dd垂直上对齐？
```
	<form action="#">
		<dl>
			<dt>请输入邮箱地址</dt><dd><input type="text" value="这是一个文本输入框"><br>邮箱地址请按要求格式输入</dd>
		</dl>
	</form>
```
