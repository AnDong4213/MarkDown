# demo2

## 链接 demo

### 内嵌式链接

- 外部链接: [百度](http://www.baidu.com)
- 内部链接: 链接仓库的其他文件: [demo1](demo1.md)
- 内部链接2: 链接本文档的其他部分: [代码块demo](demo2.md#代码块-demo)

### 引用式链接

- 外部链接: [百度]
- 外部链接: [百度][baidu]
- 内部链接: 链接仓库的其他文件: [demo1]
- 内部链接2: 链接本文档的其他部分: [代码块demo]


## 图片 demo

- 图片的MarkDown语法
  - 外部图片 demo  <!--- ![alt](url text) -->
![baidu](https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/logo_white_fe6da1ec.png '我是提示文字')

  - 仓库内的图片 demo  
![](images/open.jpg)

- 图片的引用式链接
  - 外部图片 demo
    ![baidu][baidu_logo]
  - 仓库内的图片 demo  
    ![][open_png]

## 引用 demo

> 这是一个引文

--出自《论语》

多重引用

>>> 这是多重引文

## 代码块 demo

- 行内代码

这个代码中用来声明变量是`let a = 10`,打印变量内容是`console.log()`函数的调用--haha

- 块式代码

```javascript
let a = 10;
console.log(a)
```

    let a = 10;
    console.log(a)(很少用)

<!--- 下面是本文档中用到的链接 -->
[百度]: http://www.baidu.com
[baidu]: http://www.baidu.com
[demo1]: demo1.md
[代码块demo]: demo2.md#代码块-demo

[baidu_logo]: https://ss0.bdstatic.com/5aV1bjqh_Q23odCf/static/superman/img/logo/logo_white_fe6da1ec.png
[open_png]: images/open.jpg
