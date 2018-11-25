





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
 - Shortcodes:Info, Warning, Colorcode, quote.  [Demo Here](https://jesselau.com/w3-simple-shortcodes-demo/)
 - Sphinx or Manticore search supported. Output xml file which can be indexed by sphinx and manticore search. Example site can not include search function because it need server-side setting. [Live Search function Demo Here](https://jesselau.com/search/)
 - Table of content and back to top button on scroll.
 - Grid style and simple list style.
 - All posts in one page. With a filterable, sortable and responsive table powered by w3.js. [Live Demo Here.](https://jesselau.com/allposts/)
 - Google translate.
 - Social icon.
 - Multilingual.
 - Glowing style logo
 - Scroll indicator

 ## Screenshot
### Grid style 
![HUGO W3 SIMPLE](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/images/tn.png)
### Simple list style
 
![HUGO W3 SIMPLE DEVICE](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/images/device.png)
 
 ### All posts in one page. With a filterable, sortable and responsive table
 
![HUGO W3 SIMPLE all posts](https://raw.githubusercontent.com/jesselau76/hugo-w3-simple/master/images/allposts.png)
 

## Install:
 ```bash
 cd themes
 git clone https://github.com/jesselau76/hugo-w3-simple.git
 ```
 
## How to configure?
 It is very simple. You can edit the example **config. toml** file from examplesite.
 

## Multilingual
Hugo W3 Simple supports multilingual. example site includes both English and Chinese version. You should put your posts on `./content/{langcode}/` folder.

## Search Page

To use search function, you need create `./content/{langcode}/search/index.md` file. Please see exampleSite folder.

## All posts

To use all posts function, you need create `./content/{langcode}/allposts/_index.md` file. Please see exampleSite folder.


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




