HTML基本结构

1、HTML基本结构

	<html> <!--根控制开始标签 -->
	<head> <!-- 头开始标签 -->
	<title>标题</title> <!-- 浏览器窗口标题 -->
	</head> <!-- 头结束标签 -->
	<body> <!-- 主体开始标签 -->
	    内容显示区域
	</body> <!-- 主题结束标签 -->
	</html> <!-- 根控制结束标签 -->

以上就是一个最基本的网页，下面为解释：

（1） HTML文档是由html、head和body三大元素构成。
（2） <html>…</html>: 表示文档最外层的元素，浏览器以<html>开始解释，到</html>结束，所有网页内容都必须放在他们之间。
（3） <head>…</head>: 表示HTML文档头标签，不显示在正文中。
（4） <title>…</title>: 表示文本的标题，它被显示在浏览器窗口的标题栏中。
（5） <body>…</body>: 表示文档的主体部分，在浏览器中要显示的内容。

2、示例

	<!DOCTYPE HTML>
	<head>
	    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
	    <title>认识html文件基本结构</title>
	</head>
	<body>
	    <h1>在本小节中，你将学会认识html文件基本结构</h1>
	</body>