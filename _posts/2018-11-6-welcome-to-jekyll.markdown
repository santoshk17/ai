---
layout: post
title:  "Script Recognition"
date:   2018-11-06 09:00:13
categories: jekyll update
permalink: /archivers/hello
---
## Introduction ##
There are 22 [official](https://en.wikipedia.org/wiki/Languages_with_official_status_in_India) languages in India. The script of these languages also varies a lot. The aim of this work is to recognize the language from the image of the script. 
For this purpose, I have picked four languages: Bengali, Gujarati, Hindi, and Telugu.
<!--more-->




## Training Data ##

The following websites are the source of my training data:

* **Wikipedia** .
* **BBC**  service websites in Bengali, Gujrati, Hindi and Telugu.

These were chosen to keep similarity of font and style across all the scripts.
Images of news articles were taken from these websites. It was ensured that only text was present in the image.

| #Images | train | validation |
|:-----:|:----:|:----:|
| 100| 70% | 30% |

> **Tips:** You can disable Disqus or 多说 on posts/pages by adding `nocomments: true` into [YAML Front Matter][frontmatter].





## Conclusion ##

EasyBook does not make the footer heavy; the link to theme could be on `about.md`:

> This website is using [laobubu](http://laobubu.net)'s theme: [EasyBook](https://github.com/laobubu/jekyll-theme-EasyBook)



## Acknowledgement ##

*[BBC Bengali](https://www.bbc.com/bengali]) 
*[BBC Gujarati]:(https://www.bbc.com/gujarati)
*[BBC Hindi]:   (https://www.bbc.com/hindi)
*[BBC Telugu]: (https://www.bbc.com/telugu)

