
# HTML 简介  

## HTML实例
```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <title>慕课网</title>
    </head>
    <body>
        <h1>我是一个标题</h1>
        <p>我是一个段落。</p>
    </body>
</html>
```

实例解释：

- `<!DOCTYPE html>`声明为 HTML 文档，这里是HTML5声明方式
- `<html>`元素是 HTML 页面的根元素
- `<head>`元素包含了文档的元（meta）数据，如 <meta charset="utf-8"> 定义网页编码格式为 utf-8（由于在大部分浏览器中直接输出中文会出现乱码，所以要在头部将字符声明为UTF-8）
- `<title>`元素描述了文档的标题
- `<body>`元素包含了可见的页面内容
- `<h1`元素定义一个大标题
- `<p>`元素定义一个段落

##  HTML是什么？
- HTML，全称“Hyper Text Markup Language（超文本标记语言）”
- HTML不是一门编程语言，而是一门描述性的标记语言
- 标记语言是一套标记标签 (markup tag)
- HTML 使用标记标签来描述网页
- HTML 文档包含了HTML 标签及文本内容
- HTML文档也叫做 web 页面

##  HTML基本语法
```
<标签符>内容</标签符>
```
- 标签符一般都是成对出现，有一个开始符号和一个结束符号，结束符号只是在开头符号的前面加一个斜杠“/”。当浏览器收到HTML文本后，就会解释里面的标签符，然后把标签符相对应的功能表达出来。
- 实例：

1. `<strong></strong>`（英语就是：强壮的，强健的）来定义粗体，当浏览器遇到`<strong></strong>`标签对的时候，就会显示成粗体

    ```
    <strong>慕课网strong标签</strong>
    ```
2. `<small></small>`（英语就是：小的意思）来定义小号字体，，当浏览器遇到`<small></small>`标签对的时候，就会显示成小号字体
    ```
    <small>慕课网strong标签</small>
    ```
- 实例运行结果：
    ![image](http://chuantu.xyz/t6/722/1583487818x2362407012.png)

## Web 浏览器
- Web浏览器是用来读取HTML文件，然后识别文件里面的标签内容，并将其作为网页显示，并不是直接显示HTML标签
- 常见的web浏览器有：谷歌浏览器chrome，Internet Explorer，Firefox，Safari，等等，对于我们开发的时候


## Tips
> ##### 
- 在HTML文档里面，只有`<body>`部分才会在浏览器中显示


