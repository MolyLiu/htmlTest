#htmlTest

这是一个html学习的简单工程。记录各种概念和demo

##基本概念
* HTTP—— Hyper Text Transfer Protocol:超文本传输协议，一般用于网页及其他文件在网络间的传输。
* HTML—— Hyper Text Markup Language:超文本标记语言，一般用于网页设计
* FTP—— File Transfer Protoco:文件传输协议，一般用于文件传输
* URL—— Uniform Resource Locators:统一资源定位器，用于定位网络上的资源

##HTML基础
### “hmtl 标签”
```
<html>..</html>
标记文档中含有超文本的内容
``` 
### "head标签"
```
<head>..</head>
html文档的头部，含有初始化信息
``` 
####head标签中常用元素
```
<meta>:用于设置一些网页头信息
<style>…</style>用于定义样式
<script language="">…</script> 用于定义页面中所使用的脚本语言
```
###“标题”
```
<title>..</title>
页面的标题
```
###“body标签”
```
<body>..</body>
文档体，包含页面所有的具体内容
```
###“超链接”
```
<a href>..</a>
超级链接
```


### 常用标签
####标题元素
* 标题元素让文字以更醒目的方式显示，往往用于文章的标题
* 基本语法：<h#>…</h#>

    - '#'=1,2,3,4,5,6
#### 列表元素
* 列表是指将具有相似特征的或者具有先后顺序的几行文字进行对其排列
* 所有的列表都由列表类型和列表项组成
    — 列表类型:有序列表ol&无序列表ul
    — 列表项：li,用于只是具体的列表内容.
####分区元素
* 分区元素用于元素分组，常用于页面布局
* 块分区元素：div
* 行内分区元素:span
    - 设置同一行文字不同格式
* 块级元素
    - 默认情况下，块级元素独占一行，即元素前后都会自动换行
    - 如：p,div,hn标签
* 行内元素
    - 不会换行，可以和其他行内元素位于同一行
    - 如：span a
* span元素是内联元素，可用作文本的容器
    -span元素也没有特定的含义，当与CSS一同使用时，span元素可用于为部分文本设置样式属性.
* 常用的行内元素
    -b & strong 字体加粗
    - i 字体倾斜
    - small 字体缩小
    - del 划线
    - u 下划线
*空格折叠：默认情况下，HTML中多个空格，多个制表符，多个换行都会被压缩成单个空格，即只显示一个空格。
*实体引用：HTML中常用的字符实体如下：
（暂不补全）
#### 图像元素
```
<img src="" align="" border=""/>
图片标记
```
* 使用img元素将图片添加到页面
    - 必须属性：src
    - 常用属性：width、height
    - 使用相对路径更好
    
#### 超链接和锚点
* 使用<a>元素创建一个超级链接，语法如下
*
```
<a href="" target="">文本</a>

```
* Href属性：链接url

* Target属性：目标打开方式
     - blank:浏览器总在一个新打开、未命名的窗口中载入目标文档。
     - parent：
     - self：
     - top
     
*页面内跳转锚点。
    - 方法一：1.设置一个锚点链接,hred属性的属性值前要加#
 