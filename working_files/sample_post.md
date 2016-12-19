---
layout: post
img: 'img/
title: ""
author: [kuba, simon]
landmark: [City]
categories: [Country]
tags: [nature, city]
description: "description to show up when sharing link"
---

[comment] <> (
This is how to include an image. copy the line below

![{{page.title}}]({{ site.url }}/{{ page.img }}/original/replace_this.jpg){:class="img-responsive center-block img-article"}

)

[comment] <> (
This is how to include a place map. Fill in landmark and make sure it's correctly spelled.

{% include place-map.html %}

)

[comment] <> (
This is how to include a directions map. Fill in origin and destination and make sure it's correctly spelled.

{% include directions-map.html %}

)
