---
title: test
date: 2024-04-04 00:31:56
index_img: ../img/post/TengineLogo.png
sticky: 100
categories: 框架学习
tags: 
 - Tengine
 - Gameframework
 - fantasy
 - yooasset
mermaid: true
---

# 以下是hexo的 tag插件显示

## 引用的使用

{% blockquote %}
这是一个普通的引用块：Lorem ipsum dolor sit amet, consectetur adipiscing elit. Pellentesque hendrerit lacus ut purus iaculis feugiat. Sed nec tempor elit, quis aliquam neque. Curabitur sed diam eget dolor fermentum semper at eu lorem.
{% endblockquote %}

{% blockquote David Levithan, Wide Awake %}
引用书上的句子的引用块Do not just seek happiness for yourself. Seek happiness for all. Through kindness. Through mercy.
{% endblockquote %}

{% blockquote @DevDocs https://twitter.com/devdocs/status/356095192085962752 %}
引用网站的引用块：NEW: DevDocs now comes with syntax highlighting. http://devdocs.io
{% endblockquote %}

{% blockquote Seth Godin http://sethgodin.typepad.com/seths_blog/2009/07/welcome-to-island-marketing.html Welcome to Island Marketing %}
引用文章的引用块Every interaction is both precious and an opportunity to delight.
{% endblockquote %}


![alt text](../img/example.jpg)
![alt text](../img/Sample14.jpg)

## 脚注的使用

这是一句话[^1]
这是第二句话[^2]
这是第二句话[^3]
注意脚注需要写在文章的最后


## 便签的使用

{% note primary %}
文字 或者 `markdown` 均可
个
{% endnote %}

{% note secondary %}
文字 或者 `markdown` 均可
{% endnote %}

{% note success %}
文字 或者 `markdown` 均可
{% endnote %}

{% note danger %}
文字 或者 `markdown` 均可
{% endnote %}

{% note warning %}
文字 或者 `markdown` 均可
{% endnote %}

{% note info %}
文字 或者 `markdown` 均可
{% endnote %}

{% note light %}
文字 或者 `markdown` 均可
{% endnote %}

## 行内标签

{% label primary @text %}
{% label default  @text %}
{% label info  @text %}
{% label success  @text %}
{% label warning  @text %}
{% label danger @text %}

## 折叠块

{% fold info @title %}
需要折叠的一段内容，支持 markdown
{% endfold %}

## 勾选框

{% cb text, true, false %}
text：显示的文字
checked：默认是否已勾选，默认 false
incline: 是否内联（可以理解为后面的文字是否换行），默认 false

## 按钮

{% btn url, text, title %}
url：跳转链接
text：显示的文字
title：鼠标悬停时显示的文字（可选）

## 组图

{% gi total n1-n2-... %}
![alt text](../img/post/3gbizhiCom-1708800406.jpg)
![alt text](../img/post/3gbizhiCom-1708857571.png)
![alt text](../img/post/3gbizhiCom-1708858358.jpg)
![alt text](../img/post/3gbizhiCom-1708858390.jpg)
{% endgi %}



[^1]: 这是对应的脚注
[^2]: 这是对应的脚注
[^3]: asdf
