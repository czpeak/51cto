# Demo2

## 链接 demo

### 内嵌式链接

- 外部链接：[百度](http://www.baidu.com)
- 内部链接1，链接仓库的其他文件：[demo1](demo1.md)
- 内部链接2，链接本文档的其他部分：[代码块 demo](demo2.md#代码块-demo)

### 引用式链接
- 外部链接[百度]
- 外部链接[百度][baidu]
- 内部链接1，链接仓库的其他文件：[demo1]
- 内部链接2，链接本文档的其他部分：[代码块 demo]

## 图片 demo

- 图片的MarkDown语法
    ![alt](url text)
- 外部图片 demo
![baidu](https://www.baidu.com/img/bd_logo1.png "百度")
- 仓库内的图片 demo
![](images/open.jpg)

图片的引用式链接
- 外部图片 demo
![baidu][baidu_logo]
- 仓库内的图片 demo
![][open]

## 引用 demo

>这是一个引文

出自《摸出》

多重引用

>>> 这是多重引文


## 代码块 demo

* 块式代码

```javascript
var a = 10
console.log(a)
```

    var a = 10
    console.log(a)

* 行内代码

这个代码中用来申明变量是`var a = 10`, 打印变量内容是`console.log`函数调用


<!-- 下面是本文档中用到的链接 -->
[百度]:http://www.baidu.com
[baidu]:http://www.baidu.com
[demo1]:demo1.md
[代码块 demo]:demo2.md#代码块-demo

[baidu_logo]:https://www.baidu.com/img/bd_logo1.png
[open]:images/open.jpg