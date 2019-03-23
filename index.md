---
layout: default
output:
  md_document:
    preserve_yaml: true
---

Welcome to my Blog
==================

![](index_files/figure-markdown_strict/unnamed-chunk-1-1.png)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>