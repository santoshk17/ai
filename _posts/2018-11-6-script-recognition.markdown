---
layout: post
title:  "Script Recognition"
date:   2018-11-06 09:00:13
categories: FastAi
permalink: /projects/fastai
---
## Introduction ##
There are 22 [official](https://en.wikipedia.org/wiki/Languages_with_official_status_in_India) languages in India. The script of these languages also varies a lot. The aim of this work is to recognize the language from the image of the script. 
For this purpose, I have picked four languages: Bengali, Gujarati, Hindi, and Telugu.
<!--more-->

## Model ##
 RESNET 34 model is used for this task with the help of  [FastAi](https://docs.fast.ai/) deep learning library.
The fastai library simplifies training fast and accurate neural nets using modern best practices. It's based on research in to deep learning best practices undertaken at fast.ai, including "out of the box" support for vision, text, tabular, and collab (collaborative filtering) models.
## Training Data ##

The following websites are the source of my training data:

* **Wikipedia** .
* **BBC**  service websites in Bengali, Gujrati, Hindi and Telugu.

These were chosen to keep similarity of font and style across all the scripts.
Images of news articles were taken from these websites. It was ensured that only text was present in the image.

| #Images | train | validation |
|:-----:|:----:|:----:|
| 100| 70% | 30% |

## Conclusion ##

The training set used consisted of neat and clear font from the above mentioned websites. This model when tested on newspaper articles, textbook articles and others has shown a very good accuracy( ~95 %).

## Result ##
{% include youtubePlayer.html id="XbOROy0C1w4" %}

## Acknowledgement ##

*[BBC Bengali](https://www.bbc.com/bengali). 
*[BBC Gujarati](https://www.bbc.com/gujarati).
*[BBC Hindi](https://www.bbc.com/hindi).
*[BBC Telugu](https://www.bbc.com/telugu).

