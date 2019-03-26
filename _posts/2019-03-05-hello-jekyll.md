---
title: Hello Jekyll!
author: Bernardo D'Auria
date: '2019-03-05'
slug: hello-jekyll
categories:
  - graphs
tags: []

layout: post
---

This is my first plot that cointains an R graph


{% highlight r %}
library(ggplot2)
ggplot(iris,aes(x=Sepal.Width,y=Sepal.Length)) + geom_point()
{% endhighlight %}

![plot of chunk unnamed-chunk-1]({{ "assets/figures/" | absolute_url }}2019-03-05-hello-jekyll/unnamed-chunk-1-1.png)

and an external picture

![colored cats](https://raw.githubusercontent.com/brdauria/codingclubuc3m_talk/master/docs/images/cats.jpg)

