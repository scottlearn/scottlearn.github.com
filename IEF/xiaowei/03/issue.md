* 使用img.member-logo无效，用注释掉的css有效，为什么？
```
<div class="rightwarp">
			<img class="menber-logo" src="../03/img/icon01.png" alt="" >
```
```
.rightwarp{float: right;padding: 20px;background-color: #fff;}
.member-logo{display: block;width:80px;height: 80px;}
/*.rightwarp img{display: block;width:80px;height: 80px;}*/
```

需要补充的知识点：？

