---
layout: main
title:  "My First post"
date:   2019-07-11 09:54:33 +0300
categories: jekyll update
author: Hristo Machikov
image:
    directory: /assets/posts/
    name: post_1
    extention: .jpg
    aspectratio:
---

{% if page.author %}
    <img src="{{ site.baseurl }}{{ page.image.directory }}{{ page.image.name }}{{ page.image.extention }}" alt="{{ page.image.name }}" width="320">
{% endif %}

# Hello!
## Hello there!!!
