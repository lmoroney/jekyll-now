---
layout: post
title: Horses or Humans CGI Data
---

Horses or Humans is a dataset of 300×300 images, created by Laurence Moroney, that is licensed CC-By-2.0 for anybody to use in learning or testing computer vision algorithms.

# Overview
When learning Computer Vision, in particular the training of DNNs and CNNs to recognize and classify images, there is a dearth of good datasets, and you tend to see the same old datasets again and again.

*I wanted to fix that problem*

I wanted a dataset that could be used for teaching binary classifiers that was unique and distinct from existing datasets.  

I wanted to see if I could use Photoreal CGI to train a neural network that could then recognize and classify real images with the same subject matter
The result is Horses-v-Humans. You can download the raw data for the training set here, and for a validation set here.

## Data
The set contains 500 rendered images of various species of horse in various poses in various locations. It also contains 527 rendered images of humans in various poses and locations. Emphasis has been taken to ensure diversity of humans, and to that end there are both men and women as well as Asian, Black, South Asian and Caucasians present in the training set. The validation set adds 6 different figures of different gender, race and pose to ensure breadth of data.

Here are some examples:  

![_config.yml]({{ site.baseurl }}/images/horse03-3.png)
![_config.yml]({{ site.baseurl }}/images/horse08-5.png)
![_config.yml]({{ site.baseurl }}/images/human01-16.png)
![_config.yml]({{ site.baseurl }}/images/human05-09.png)

**All Images are 300×300 pixels in 24-bit color.**

They’re arranged into sub folders within the zip that makes it easy to auto label them using a Keras ImageGenerator

### License
The dataset is licensed as a CC By 2.0, free for you to share and adapt for all uses, commercial or non-commercial. Please just attribute and give appropriate credit to Laurence Moroney (lmoroney@gmail.com / laurencemoroney.com), and place no additional restrictions on your users as outlined here.
