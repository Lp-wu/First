# 严格的html
1. ## 告诉浏览器使用的是html4.0
在html的文件顶部加一行语句：`<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 4.01//EN"
   "http://www.w3.org/TR/html4/strict.dtd">`添加在第一行
2. ## html4.01中，`<img>`元素中必须添加一个alt属性。
3. ## 添加`<meta>`标记
`<meta http-equiv="Content-Type" Content="text/html; charset=ISO-8859-1">`大多数欧洲语言都要使用；添加在`head`元素的开头
4. ## 内联元素要嵌套到块元素中
5. ## <html>元素必不可少；网页总是以一个DOCTYPE开始，紧接着，<html>元素必须出现在网页的开头和结尾。
6. ## 只使用有用的块元素填充<body>
只能在<body>元素里直接放置块元素（<h1>,<h2>,...,<h6>,<p>,<blockqoute>等）。所有内联元素和文本都必须在块元素中才能运行。
7. ## 让块元素远离内联元素
只有文本和其他内联元素可以嵌在内联元素中。块元素在任何情况下都不允许包含在内联元素里。
8. ## 块元素禁止包含在<p>元素之中。
只有文本才能组成段落，所有块元素不允许包含在<p>元素中，当然，只要你喜欢，可以在段落里使用所有的内联元素（<em><a><strong><img><q>）
9. ## 列表只能包括列表项目
只有<li>元素允许放在<ul>和<ol>元素里。因此只有列表项才能放在有序或无序列表里
# 严格的xhtml
1. ## 开头加上`<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Strict//EN"
   "http://www.w3.org/TR/xhtml1/DTD/XHTM11-strict.dtd"`
2. ## 空元素末尾有一个/> 例如：`<img src="drink.gif" alt="the drinks"/>`
3. ## 添加xmlns属性，lang属性和xml：lang属性到<html>开始标记`<html xmlns="http://www.w3.org/1999/xhtml" lang="en" xml:lang="en">`
