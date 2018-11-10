


# Hugo W3 SIMPLE

## _Keep it simple, but not simpler_


**Hugo W3 Simple** is a Hugo theme written by [Jesse Lau](https://jesselau.com) . The main motivation for writing this theme was to provide a really minimal theme with W3 CSS included. 


## Screenshot

![Hugo W3 Simple](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/images/screenshot.png)![Jesse Lau Blog](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/images/tn.png)
## Features:

 - W3.css - small and fast
 - Responsive
 - W3 code color js - small and fast code highlight solution. 
 - Twitter Card
 - Google Analytics
 - Disqus
 - One Signal Push
 - Social share & Bookmark bar
 - Shortcodes:Info, Warning, Colorcode.  [Demo Here](https://jesselau.com/w3-simple-shortcodes-demo/)
 

## Install:
 ```bash
 cd themes
 git clone https://github.com/jesselau76/hugo-w3-simple.git
 ```
 
## How to configure?
 It is very simple. You can edit the example **config. toml** file below
 

```bash
baseurl = "https://example.org/"
languageCode = "en-us"
title = "Hugo W3 Simple Theme"
theme = "hugo-w3-simple"
disqusShortname = ""      # disqus_shortname
googleAnalytics = ""      # UA-XXXXXXXX-X


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


[params]
    relatedPosts = true
    socialshare = true
    searchfunction = false #If you need search button and you have search function please set true
    description = "Hugo W3 Simple Theme"
    onesignalid = ""  #one signal push app id
    logotext = "HUGO W3 SIMPLE" # logo text
    footer = "&copy; [Jesse Lau](https://jesselau.com) 2018 | [Github](https://github.com/jesselau76) | [Twitter](https://twitter.com/jesselau2)  | [RSS](/index.xml)"

