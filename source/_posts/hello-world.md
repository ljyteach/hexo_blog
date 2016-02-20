---
title: Markdown语法说明
date: 2016-01-26 08:08:02
tags: md
---

markdown语法入门,有待完善～修改中！

## 标题
``` md
# h1
## h2
### h3
#### h4
##### h5
###### h6
```

## 代码
\`\`\`
	//这里面是代码
\`\`\`  

``` js
alert("hello markdown");
console.log("hello markdown");

```

## 连接
跳转到百度：[百度](http://baidu.com)
``` md
跳转到百度：[百度](http://baidu.com)
```

## 无序列表
+ 香蕉
+ 苹果
+ 鸭梨
+ 水蜜桃

``` md
+ 香蕉
+ 苹果
+ 鸭梨
+ 水蜜桃
```

## 分隔线

分隔线
********

``` md
分隔线
********
```

## em标签和strong标签
*这是一段普通的文字*
**这是一段普通的文字**
```
*这是一段普通的文字*
**这是一段普通的文字**
```

## 反斜杠转义
Markdown 支持以下这些符号前面加上反斜杠来帮助插入普通的符号：
``` bash
\   反斜线
`   反引号
*   星号
_   底线
{}  花括号
[]  方括号
()  括弧
#   井字号
+   加号
-   减号
.   英文句点
!   惊叹号
```
## 最后附上一张图片
``` md
![Alt text](/path/to/img.jpg "Optional title")
```
![picture](/img/banner.jpg "美丽的景色")
