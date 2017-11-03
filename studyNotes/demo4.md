# demo4

## 混合强调样式
* **加粗**
* *倾斜*
* ~~删除~~

混合强调样式：
* ***加粗倾斜***
* **~~加粗删除~~**
* ~~*删除*~~
* ***~~加粗倾斜删除~~***

## 图片链接

基本文字链接
[链接文字](URL)

[百度](http://www.baidu.com)

基本图片
![alt](url text)

![baidu](http://www.baidu.com/img/bd_logo1.png '百度')

图片链接
[![](http://www.baidu.com/img/bd_logo1.png)](http://www.baidu.com)
[![](baidu_logo)](baidu)

引用连接问题
good:
[百度][baidu]
[百度网址][baidu]

low:
[百度]
[百度网址]
<!-- 链接 -->

[baidu]:http://www.baidu.com
[baidu_logo]:http://www.baidu.com/img/bd_logo1.png
[百度]:http://www.baidu.com
[百度网址]:http://www.baidu.com

## 多级列表
- 问题1：如何打断：空行不行  加文字段落
1. item1
  1. item1.1
  2. item1.2
2. item2
打断列表
3. item3


4. item4
- 问题2：打断的列表，如何接上 文字前加空行缩进
1. item1
  1. item1.1
  2. item1.2
2. item2

    打断列表

3. item3


4. item4

- item1
  - item1.1
  - item1.2
- item2
- item3
