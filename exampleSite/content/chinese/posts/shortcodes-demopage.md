
---
author: admin
date: 2018-11-24T00:26:15+13:00
draft: false
title: Hugo W3 Simple主题快捷方式演示
url: /hugo-w3-simple-shortcodes-demo/
w3codecolor: true
categories:
- 网络开发
tags:
- hugo

type:  "post"
thumbnail: https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/exampleSite/images/thumb-jad-limcaco-183877-unsplash.jpg

---

关于这个模板 [Hugo W3-Simple Theme](https://github.com/jesselau76/hugo-w3-simple)我是先做了个英文版的快捷方式演示，因为考虑到可能英文用户会稍微多点，今天有空又更新了一个快捷方式，同时写一个中文版页面吧。

此模板是基于[W3schools](https://www.w3schools.com/w3css/default.asp) 的W3.CSS框架做成的，因为我觉得此框架十分有效而且简洁，比bootstrap的css要小的多。  

W3.css只有bootstrap css的五分之一不到。我还没有算上boostrap的javascript库。  

通过这个css框架，可以很方便的做一些快捷方式来丰富博客的内容。
<hr>

# Info 快捷方式
我们可以很简单的在markdown文件中显示一些信息：
{{< colorcode title="Code for info shortcodes">}}  
{{&lt; info  &gt;}}<br>  
蓝色常常指示一些信息性内容<br> 
{{&lt;/info &gt;}}  
{{< /colorcode >}}  
这个标题缺省的是 `Information!`:  
{{< info  >}}  
蓝色常常指示一些信息性内容 
{{< /info >}}    

我们可以设置标题

{{< colorcode title="Code for info shortcodes with title">}}  
{{&lt; info  title="W3.CSS是一个CSS框架!"&gt;}} <br> 
W3.CSS是一个自适应的CSS框架。 它默认支持移动设备自适应设计，并且比类似的CSS框架更小更快。<br> 
{{&lt; /info &gt;}}  
{{< /colorcode >}}  
 
{{< info  title="W3.CSS是一个CSS框架!">}}  
W3.CSS是一个自适应的CSS框架。 它默认支持移动设备自适应设计，并且比类似的CSS框架更小更快。
{{< /info >}}  

<hr>

# Warning 快捷方式
我们也可很简单的显示警告信息
{{< colorcode title="Code for warning shortcodes">}}  
{{&lt; warning  &gt;}}<br>  
黄色常常用于设置警告标识 <br> 
{{&lt;/warning &gt;}}  
{{< /colorcode >}}  
这个标题缺省是 `Warning!`:  
{{< warning  >}}  
黄色常常用于设置警告标识
{{< /warning >}}    

可以自设标题：

{{< colorcode title="Code for warning shortcodes with title">}}  
{{&lt; warning title="注意!"&gt;}} <br> 
W3 CSS比其他CSS模板小上n倍，故此速度更快 <br> 
{{&lt; /warning &gt;}}  
{{< /colorcode >}}  
It will display the title with your set:  
{{< warning  title="注意!">}}  
W3 CSS比其他CSS模板小上n倍，故此速度更快
{{< /warning >}}  

<hr>

# Colorcode 快捷方式
本模板仍然是用w3schools的一个w3colorcode.js来显示代码颜色，为啥用它呢，还是因为它足够小，比highlight.js小上n倍。    

要用这个功能，你需要在帖子的markdown文件设置 `w3codecolor: true` .   

因为这个js文件虽然比其他的都小得多，但也有20kb以上，所以我没有设成全站所有文件都调用这个js文件，毕竟很多帖子根本不需要显示代码颜色。  

w3colorcode.js的原版在w3schools目前支持`html`, `js`, `java`, `css`, `sql`, `python` 的颜色高亮。

我稍微更改了一下，让它支持了`bash` 脚本语言的高亮。  

## bash 语言高亮

Colorcode 快捷方式用 `mode` 和`title` 两个参数来设置. 假如不设置，就缺省采用`bash`语言高亮，也没有任何标题.  

{{< colorcode title="Code for default colorcode shortcodes">}}  
{{&lt; colorcode  &gt;}}<br>  
your code here<br> 
{{&lt;/colorcode &gt;}}  
{{< /colorcode >}}  
The demo for default colorcode shortcodes:
{{< colorcode >}}  
欲安装Hugo-w3-simple主题模板,用下列命令即可<br>
cd themes<br>
git clone https://github.com/jesselau76/hugo-w3-simple.git<br> 
{{< /colorcode >}}  

## html 语言高亮
{{< colorcode title="Code for html colorcode shortcodes">}}  
{{&lt; colorcode mode="htmlHigh" title="Demo for html color" &gt;}}<br>  
your code here<br> 
{{&lt;/colorcode &gt;}}  
{{< /colorcode >}}  

{{< colorcode mode="htmlHigh" title="Demo for html color" >}}  
&lt;!DOCTYPE html&gt;<br>&lt;html&gt;<br>
    &lt;title&gt;HTML Tutorial&lt;/title&gt;<br>
    &lt;body&gt;<br><br>
    &lt;h1&gt;This is a heading&lt;/h1&gt;<br>
    &lt;p&gt;This is a paragraph.&lt;/p&gt;<br><br>
    &lt;/body&gt;<br>
    &lt;/html&gt; 
{{< /colorcode >}}  

## css 语言高亮

{{< colorcode title="Code for css colorcode shortcodes">}}  
{{&lt; colorcode mode="cssHigh" title="Demo for css color" &gt;}}<br>  
your code here<br> 
{{&lt;/colorcode &gt;}}  
{{< /colorcode >}}  

{{< colorcode mode="cssHigh" title="Demo for css color" >}}  
body {<br>
    background-color: #d0e4fe;<br>
    }<br><br>

    h1 {<br>
    color: orange;<br>
    text-align: center;<br>
    }<br><br>

    p {<br>
    font-family: "Times New Roman";<br>
    font-size: 20px;<br>
    }
{{< /colorcode >}}  

## javascript语言高亮

{{< colorcode title="Code for js colorcode shortcodes">}}  
{{&lt; colorcode mode="jsHigh" title="Demo for js color" &gt;}}<br>  
your code here<br> 
{{&lt;/colorcode &gt;}}  
{{< /colorcode >}}  

{{< colorcode mode="jsHigh" title="Demo for js color" >}}  
function w3CodeColor() {<br>
  var x, i, j, k, l, modes = ["html", "js", "java", "css", "sql", "python"];<br>
  if (!document.getElementsByClassName) {return;}<br>
  k = modes.length;<br>
  for (j = 0; j < k; j++) {<br>
    x = document.getElementsByClassName(modes[j] + "High");<br>
    l = x.length;<br>
    for (i = 0; i < l; i++) {<br>
      x[i].innerHTML = w3CodeColorize(x[i].innerHTML, modes[j]);<br>
    }<br>
  }<br>
}<br>
{{< /colorcode >}}  

## sql 语言高亮
{{< colorcode title="Code for sql colorcode shortcodes">}}  
{{&lt; colorcode mode="sqlHigh" title="Demo for sql color" &gt;}}<br>  
your code here<br> 
{{&lt;/colorcode &gt;}}  
{{< /colorcode >}}  

{{< colorcode mode="sqlHigh" title="Demo for sql color" >}}  
SELECT column1, column2, ...<br>  
FROM table_name<br>  
ORDER BY column1, column2, ... ASC|DESC; <br>  
{{< /colorcode >}}  

## python语言高亮
{{< colorcode title="Code for python colorcode shortcodes">}}  
{{&lt; colorcode mode="pythonHigh" title="Demo for python color" &gt;}}<br>  
your code here<br> 
{{&lt;/colorcode &gt;}}  
{{< /colorcode >}}  

{{< colorcode mode="pythonHigh" title="Demo for python color" >}}  
import json<br>

# some JSON:<br>
x =  '{ "name":"John", "age":30, "city":"New York"}'<br>

# parse x:<br>
y = json.loads(x)<br>

# the result is a Python dictionary:<br>
print(y["age"]) <br>
{{< /colorcode >}}  

<hr>

# quote 快捷方式

本来用`blockquote`也可以显示引文。不过有时我们想多样化显示。所以我也做了这个一个快捷方式。

{{< colorcode title="Code for quote shortcodes">}}  
{{&lt; quote  &gt;}}<br>  

    天地不仁，以万物为刍狗；圣人不仁，以百姓为刍狗。<br> 

{{&lt; /quote &gt;}}  
{{< /colorcode >}}  
缺省宽度为100%，不显示作者
{{< quote  >}}  

     天地不仁，以万物为刍狗；圣人不仁，以百姓为刍狗。

{{< /quote >}}  

可以设置宽度百分比，设置作者信息
 {{< colorcode title="Code for quote shortcodes with % width">}}  
{{&lt; quote width="38.2%" author="老子"  &gt;}}<br>  

    天地不仁，以万物为刍狗；圣人不仁，以百姓为刍狗。<br> 

{{&lt; /quote &gt;}}  
{{< /colorcode >}}  
{{< quote width="38.2%" author="老子" >}}  

     天地不仁，以万物为刍狗；圣人不仁，以百姓为刍狗。

{{< /quote >}}   

也可以直接设置px宽度

{{< colorcode title="Code for quote shortcodes with px width">}}  
{{&lt; quote width="300px"  author="老子" &gt;}}<br>  

     天地不仁，以万物为刍狗；圣人不仁，以百姓为刍狗。<br> 

{{&lt; /quote &gt;}}  
{{< /colorcode >}}  

{{< quote width="300px" author="老子" >}}  

     天地不仁，以万物为刍狗；圣人不仁，以百姓为刍狗。

{{< /quote >}}   

