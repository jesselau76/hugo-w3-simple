



# Hugo W3 SIMPLE

## _Keep it simple, but not simpler_


**Hugo W3 Simple** is a Hugo theme written by [Jesse Lau](https://jesselau.com) . The main motivation for writing this theme was to provide a really minimal theme with W3 CSS included. 


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
 - Sphinx or Manticore search supported. Output xml file which can be indexed by sphinx and manticore search. Example site can not include search function because it need server-side setting. [Live Search function Demo Here](https://jesselau.com/search/)
 - Table of content on sidebar.
 - Grid style and simple list style.
 - All posts in one page. With a filterable, sortable and responsive table powered by w3.js. [Live Demo Here.](https://jesselau.com/allposts/)

 ## Screenshot
### Grid style 
![HUGO W3 SIMPLE](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/images/tn.png)
### Simple list style
 
![HUGO W3 SIMPLE DEVICE](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/images/device.png)
 

## Install:
 ```bash
 cd themes
 git clone https://github.com/jesselau76/hugo-w3-simple.git
 ```
 
## How to configure?
 It is very simple. You can edit the example **config. toml** file from examplesite or below
 

```bash
baseurl = "https://example.com/"
languageCode = "en-us"
title = "Hugo W3 Simple Theme"
theme = "hugo-w3-simple"
disqusShortname = ""      # disqus_shortname
googleAnalytics = ""      # UA-XXXXXXXX-X
paginate = 12 #gridstyle use 3 column. so should be 3,6,9,12,15....

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
    name = "All Posts"
    url = "/allposts/"
    weight = 5



[params]
    relatedPosts = true
    gridstyle = true  # list post with grid style. If false then simple list
    readingtime = true  #display reading time and word count
    firstpic = true  # display first picture as thumbnail if no thumbnail set. For gridstyle only
    socialshare = true
    searchfunction = false #If you need search button and you have search function please set true
    description = "Hugo W3 Simple Theme"
    onesignalid = ""  #one signal push app id
    logotext = "HUGO W3 SIMPLE" # logo text
    footer = "&copy; [Jesse Lau](https://jesselau.com) 2018 | [Github](https://github.com/jesselau76) | [Twitter](https://twitter.com/jesselau2)  | [RSS](/index.xml)"
```    

## Search Page

To use search function, you need create `./content/search/index.md` file. Please see exampleSite folder.

## All posts

To use all posts function, you need create `./content/allposts/_index.md` file. Please see exampleSite folder.


## Favicon

In order to customize the favicon you need to place the `favicon.ico` file in the static folder at the root of your site, which will overwrite those files in the themes/even/static/ folder.


## Update Theme

```bash
cd  themes/hugo-w3-simple/
git pull
```

## License

Released under the [MIT](https://github.com/jesselau76/hugo-w3-simple/blob/master/LICENSE) License.

## Acknowledgements

- [Hugo Xmin](https://github.com/yihui/hugo-xmin)
- [Even](https://github.com/olOwOlo/hugo-theme-even)
- [Mediumish](https://github.com/lgaida/mediumish-gohugo-theme)


