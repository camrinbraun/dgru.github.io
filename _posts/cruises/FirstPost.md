---
layout: page
subheadline:  "Headers With Style"
title:  "No Header but Article Image"
teaser: "Feeling Responsive enables you to get the attention of visitors. If you don't want to use a big header, use an image for the article instead."
categories:
    - design
tags:
    - design
    - background color
    - header
header: no
image:
    title: unsplash_eagle.jpg
    caption: This is a caption for the header image with link
    caption_url: https://unsplash.com/
---
First turn of the header with `header: no`. Than add an image to with the following code. The caption is optional.

~~~
header: no
image:
    title: unsplash_eagle.jpg
    caption: This is a caption for the header image with link
    caption_url: https://unsplash.com/
~~~


### All Header-Styles
{: .t60 }
{% include list-posts.html entries='3' offset='1' category='design' %}
{% include list-posts.html tag='header' %}