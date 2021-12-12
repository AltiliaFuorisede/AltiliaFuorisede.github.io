---
title: "Altilia Fuorisede"
layout: splash
permalink: /
date: 2021-12-12T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: linear-gradient(rgba(255, 0, 0, 0.5), rgba(0, 255, 225, 0.5))
  overlay_image: /assets/images/unsplash-image-1.jpg
  actions:
  - url: "/about/"
excerpt: "Circolo Arci di Altilia (kr)"
intro: 
  - excerpt: '_"Tutti compresi"_ [Cit.]'
feature_row2:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
    alt: "placeholder image 2"
    title: "Placeholder Image Left Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}

# Gli ultimi articoli postati:
{% for post in site.posts limit: 3 %}
  {% include archive-single.html %}
{% endfor %}