<!DOCTYPE HTML>
<html>
<head>
<meta  charset="utf-8">
<title>父元素高度确定的多行文本</title>
<style>
.container{
    height:300px;
	background:#ccc;
	
	display:table-cell;/*IE8以上及Chrome、Firefox*/
	vertical-align:middle;/*IE8以上及Chrome、Firefox*/
}
</style>
</head>

<body>
<div class="container">
    <div>
        <p>居中</p>
        <p>居中</p>
        <p>居中</p>
        <p>居中</p>
        <p>居中</p>
    </div>
</div>
<div>
    <img src="http://img.mukewang.com/54ffac56000169c001840181.jpg" title="害羞的小女生"/>
</div>
</body>
</html>
