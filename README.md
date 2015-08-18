针对中文,演示Markdown的各种语法
  
大标题
===================================
  大标题一般显示工程名,类似html的\<h1\><br />
  你只要在标题下面跟上=====即可

  
中标题
-----------------------------------
  中标题一般显示重点项,类似html的\<h2\><br />
  你只要在标题下面输入------即可
  
### 小标题
  小标题类似html的\<h3\><br />
  小标题的格式如下 ### 小标题<br />
  注意#和标题字符中间要有空格

### 注意!!!下面所有语法的提示我都先用小标题提醒了!!! 

### 单行文本框
    这是一个单行的文本框,只要两个Tab再输入文字即可
        
### 多行文本框  
    这是一个有多行的文本框
    你可以写入代码等,每行文字只要输入两个Tab再输入文字即可
    这里你可以输入一段代码

### 比如我们可以在多行文本框里输入一段代码,来一个Java版本的HelloWorld吧
    public class HelloWorld {

      /**
      * @param args
	    */
	    public static void main(String[] args) {
		    System.out.println("HelloWorld!");

	    }

    }
### 链接
1.[点击这里你可以链接到www.google.com](http://www.google.com)<br />
2.[点击这里我你可以链接到我的博客](http://guoyunsky.iteye.com)<br />

###只是显示图片
![github](http://github.com/unicorn.png "github")

###想点击某个图片进入一个网页,比如我想点击github的icorn然后再进入www.github.com
[![image]](http://www.github.com/)
[image]: http://github.com/github.png "github"

### 文字被些字符包围
> 文字被些字符包围
>
> 只要再文字前面加上>空格即可
>
> 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
> 但> 只能放在行首才有效

### 文字被些字符包围,多重包围
> 文字被些字符包围开始
>
> > 只要再文字前面加上>空格即可
>
>  > > 如果你要换行的话,新起一行,输入>空格即可,后面不接文字
>
> > > > 但> 只能放在行首才有效

### 特殊字符处理
有一些特殊字符如<,#等,只要在特殊字符前面加上转义字符\即可<br />
你想换行的话其实可以直接用html标签\<br /\>



* 在行首加点
行首输入*，空格后输入内容即可
    



#Markdown demo

This is a demonstration of how to use Markdown to write README.  
This file would demonstrate two syntax.  

- the traditional (original) Markdown
- GitHub Flavored Markdown.

**本文档部分摘抄整理自以下几篇文章**  

1. [markdown syntax 原作者](http://daringfireball.net/projects/markdown/syntax "markdown syntax 原作者") on daringfireball.net 
2. [上文的简体中文翻译](http://wowubuntu.com/markdown/basic.html) from wowubuntu.com
3. [献给写作者的 Markdown 新手指南 ](http://jianshu.io/p/q81RER#login-modal)from 简书
4. <http://www.ituring.com.cn/article/504>

## 目录

- 传统 Markdown
    - 标题
	- 段落
	- 加粗和斜体
	- 引用
	- 列表
	- 超链接
	- 图片
	- 代码
	- 分隔线
	- 自动链接
	- 转义字符
- GitHub 风格 Markdown
    - 换行(GFM)
    - 斜体(GFM)
    - 自动链接(GFM)
    - 删除线(GFM)
    - 代码段和代码高亮(GFM)
    - 任务列表(GFM)

## 标题
	
注意 \# 和字之间要有空格

	This is an H1
	=============
 
	This is an H2
	-------------
	
	# This is an H1
	## This is an H2
	### This is an H3
	#### This is an H4
	##### This is an H5
	###### This is an H6

## 段落

1. 正常的段落不要使用任何空格或者TAB缩进  
2. 连续回车分段
3. 行尾使用2个空格换行

## 加粗和斜体
可以使用\_或者\#

	*斜体*		_斜体_
	**加粗**		__加粗__
	
## 引用

使用\>添加区域引用

	> This is a blockquote.
	> 
	> This is the second paragraph in the blockquote.
	>
	> ## This is an H2 in a blockquote

## 列表

- 无序列表 使用（星号，加号，减号）+ **空格**
- 有序列表使用数字+点+**空格**  
- 列表中的项可以有多行，只要在开头放一个tab或者四个空格即可

## 超链接

- 行内形式
- 参考形式

title是可选的,title 的作用是会出现一个浮动的提示信息，信息内容由title给出。

	行内
	This is an [example link](http://example.com)
	This is an [example link](http://example.com/ "With a Title")
	
	参考
	I get 10 times more traffic from [Google][1] than from
	[Yahoo][2] or [MSN][3]
	
	[1]: http://google.com/        "Google"
	[2]: http://search.yahoo.com/  "Yahoo Search"
	[3]: http://search.msn.com/    "MSN Search"
	
## 图片

- 行内形式
- 参考形式

同上，title是可选的。

	行内
	![alt text](/path/to/img.jpg "Title")
	
	参考
	![alt text][id]

	[id]: /path/to/img.jpg "Title"

## 代码

- 反引号
- TAB or 4 space

使用反引号插入代码( \` )  
如果需要插入反引号就使用两个反引号，用空格分开  
起始端后面一个，结束端前面一个  
	`` `foo` ``


## 分隔线

你可以在一行中用三个或以上的星号、减号、底线来建立一个分隔线，行内不能有其他东西。你也可以在星号中间插入空白。下面每种写法都可以建立分隔线：

	* * *
	
	***
	
	*****
	
	- - -
	
	------

## 自动链接
	
	<http://example.com/>

## 转义字符
	
	\   反斜杠
	`   反引号
	*   星号
	_   底线
	{}  大括号
	[]  方括号
	()  括号
	#   井字号
	+    加号
	-    减号
	.   英文句点
	!   惊叹号

## 换行(GFM)

GFM中，换行可以不用在行尾加两个空格
第一行（不加空格）
第二行	

## 斜体(GFM)

GFW中字符串中间的下划线会被忽略
比如 `perform_complicated_task do_this_and_do_that_and_another_thing`  
perform_complicated_task do_this_and_do_that_and_another_thing
	
## 自动链接(GFM)

GFW中直接添加URL就好，比如 https://github.com 

## 删除线(GFM)

	~~Mistaken text.~~
显示成
~~Mistaken text.~~

## 代码段和代码高亮(GFM)

	Here's an example:
	
	```
	function test() {
	  console.log("notice the blank line before this function?");
	}
	```
显示成

Here's an example:

```
function test() {
  console.log("notice the blank line before this function?");
}
```

针对某种代码，可以指明

	```ruby
	require 'redcarpet'
	markdown = Redcarpet.new("Hello World!")
	puts markdown.to_html
	```

显示成

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```

## 任务列表(GFM)

	- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
	- [x] list syntax required (any unordered or ordered list supported)
	- [x] this is a complete item
	- [ ] this is an incomplete item

显示成

- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item

