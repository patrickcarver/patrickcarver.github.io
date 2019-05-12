---
layout: post
title: Kernel Functions in a Pipeline
date: 2019-05-12
categories: elixir
---

Handy tip: You can use the Kernel version of mathematical operators in a pipeline.

{% highlight elixir %}
data
|> Kernel.+(4)
|> Kernel.*(4)
|> Kernel./(5)
{% endhighlight %}