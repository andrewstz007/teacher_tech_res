Header 1
========

Header 2
--------
# 一级标题
## 二级标题
### 教程
#### 教程11
##### 教程22
###### 教程33
## 换行
一行结尾要有两个以上空格才会在显示的时候换行。  

## 列表

* 教程11
* 教程22

1. 教程11
2. 教程22

## 引用
> 如果你需要引用一小段别处的句子，那么就要用引用的格式
> > 如果你需要引用一小段别处的句子，那么就要用引用的格式

## 图片与链接
### 图片 参考图片
插入链接与插入图片的语法很像，区别在一个 !号
图片为：![alt text](http://mouapp.com/Mou_128.png =50x40){ImgCap}{/ImgCap}
图片为：![alt text](markdownImages/info.jpg =60x90)
[id]: markdownImages/info.jpg =60x90 "Title"
这是参考图片：
![alt text][id]

### 链接 Reference-style
链接为：[百度](http://www.baidu.com "alt标题1")
[id1]:http://www.baidu.com "alt标题2"
[参考链接][id1]

插入图片的地址需要图床，这里推荐[围脖图床修复计划](http://weibotuchuang.sinaapp.com/) 与 [CloudApp](http://www.getcloudapp.com/) 的服务，生成URL地址即可。
### email
An email <example@example.com> link.

## 粗体与斜体
Markdown 的粗体和斜体也非常简单，**用两个 * 包含一段文本就是粗体的语法**，*用一个 * 包含一段文本就是斜体的语法*。
## 表格
表格是我觉得 Markdown 比较累人的地方，例子如下：

| Tables        | Are           | Cool      |
| ------------- |:-------------:| --------: |
| col 3 is      | right-aligned | $1600     |
| col 2 is      | centered      |   $12     |
| zebra stripes | are neat      |    $1     |

## 代码框
### Inline Code
`<code>` spans are delimited
by backticks.

You can include literal backticks
like `` `this` ``.
### Block Code
Indent every line of a code block by at least 4 spaces or 1 tab.
This is a normal paragraph.

    This is a preformatted
    code block.
    
    
## 分割线
***
---

Part Ⅱ. Extra Syntax
========
[这里有个锚点](#anchor1)
That's some text with a footnote.[^1]  
啊啊啊   
啊啊啊  
啊啊啊  
啊啊啊  
啊啊啊  
啊啊啊   
啊啊啊  
### 脚标  
[^1]: And that's the footnote.  这个参考链接会到上面的^1处

### 删除线
~~Strikethrough~~
### 栅栏代码块
***如果三个点的上一行是普通文本，那么就得多敲个空行才行。***

```
 Fenced code blocks are like Stardard
Markdown’s regular code blocks, except that
they’re not indented and instead rely on a
start and end fence lines to delimit the code
block.
```
	和上面的tab键的一样效果呀。
	
### 简单表格
First Header | Second Header | Third Header
------------ | ------------- | ------------
表格最纠结，不用更好 | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell


First Header | Second Header | Third Header
:----------- | :-----------: | -----------:
Left         | Center        | Right
Left         | Center        | Right

### [锚点](id:anchor1)


