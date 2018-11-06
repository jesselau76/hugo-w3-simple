
# W3 SIMPLE

## _Keep it simple, but not simpler_


**W3 Simple** is a Hugo theme written by [Jesse Lau](https://jesselau.com) . The main motivation for writing this theme was to provide a really minimal theme with W3 CSS included. 

I was just tired of my Wordpress Elegant Themes and wanted to make a simple Wordpress Themes based on W3 CSS.

However, when I googled "W3 Wordpress Themes" 3 days ago, I could not find any wordpress themes but found one Hugo theme named W3 basic.

I knew Hugo at that time. 

I can't help to want to migrate Wordpress to Hugo. But I found W3 basic theme was not really basic to me who is new to Hugo.

So I made this simple one.

## Screenshot

![W3 Simple](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/images/screenshot.png)![Jesse Lau Blog](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/images/tn.png)
## Features:

 - W3.css - small and fast
 - Responsive
 - W3 code color js - small and fast code highlight solution. Less than half of highlights.js. [Demo Here](https://jesselau.com/start-blogging-today/)
 

## Install:
 ```
 cd themes
 git clone https://github.com/jesselau76/hugo-w3-simple.git
 ```
 
## How to configure?
 It is very simple. You can edit the example **config. toml** file below
 

```
baseurl = "/"
languageCode = "en-us"
title = "Jesse Lau Blog"
theme = "w3-simple"
disqusShortname = "yourdisqusshortname"      # disqus_shortname
googleAnalytics = "UA-12345678-1"      # UA-XXXXXXXX-X

[[menu.main]]
    name = "About"
    url = "/about/"
    weight = 2
[[menu.main]]
    name = "Categories"
    url = "/categories/"
    weight = 3
[[menu.main]]
    name = "Tags"
    url = "/tags/"
    weight = 4
[[menu.main]]
    name = "Subscribe"
    url = "/index.xml"

[params]
    relatedPosts = true
    description = "Jesse Lau Blog"
    footer = "&copy; [Jesse Lau](https://jesselau.com) 2018 | [Github](https://github.com/jesselau76) | [Twitter](https://twitter.com/jesselau2)"
```

## Hugo is really fast
 I just migrated my site from Wordpress to Hugo static page.
 The speed is 3 times faster.
 Here is the web page test result for Wordpress :
 ![wordpress](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/webpagetest-without-cache.png)Load Times **7.450s**
 And here is the new test with same page:
 ![hugo](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/webpagetest-hugo.png)The load times is **1.962s** now!
