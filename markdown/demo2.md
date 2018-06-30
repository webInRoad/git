# 链接Demo
	
## 内嵌式链接(行内式)
格式:

	[链接显示文字](链接地址 "title(可选)")
* 外部链接:[百度](http://www.baidu.com)
* 内部链接1,链接仓库的其他文件:[demo1](demo1.md)
* 内部链接2,链接到本文档的其他部分:[代码块 demo](demo2.md#代码块-demo)(-相当于空格)
## 引用式链接(参考式)
格式:
	
	[链接显示文字][辨识链接的标记，即链接定义的名字],  
隐式链接标记功能让你可以省略指定链接标记，此时链接标记会视为等同于链接文字
- 外部链接:[百度][]
- 等同于上面:[百度]
- 外部链接:[百度][baidu]
- 内部链接1,链接仓库的其他文件：[demo1]
- 内部链接2,链接本文档的其他部分：[代码块 demo]
# 图片Demo

## 内嵌式图片(行内式) 
1.格式:
	
	![alt text](/path/to/img.jpg "Title")  
详细叙述如下: 

* 一个惊叹号 !
* 接着一个方括号，里面放上图片的替代文字
* 接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上 选择性的 'title' 文字。  

2.实际demo
* 外部图片 demo
![百度LOGO](https://www.baidu.com/img/bd_logo1.png "百度图片")
* 仓库内的图片 demo
![](images/cover.jpg)

## 图片的引用式链接(参考式)
1.格式

	![Alt text][id],其中「id」是图片参考的名称
2.实际demo
- 外部图片 demo
![百度LOGO][baidu_logo]
- 仓库内的图片 demo
![][cover_png]

# 引用Demo

# 代码块 Demo

<!-- 下面是本文档中用到的链接  格式[链接标记] :链接地址 "title(可选)"-->

[百度]: http://www.baidu.com "百度链接"
[baidu]: http://www.baidu.com
[demo1]: demo1.md
[代码块 demo]: demo2.md#代码块-demo

[baidu_logo]:https://www.baidu.com/img/bd_logo1.png
[cover_png]:images/cover.jpg



