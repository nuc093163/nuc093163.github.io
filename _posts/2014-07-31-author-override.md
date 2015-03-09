---
layout: post
title: "博客汇总"
author: billy_rick
modified:
excerpt: "A post to test author overrides using a data file."
tags: []
---

[livoras 戴嘉华 使用git和github进行协同开发流程](http://livoras.com/post/28)

{% highlight yaml %}
# Authors

cornelius_fiddlebone:
  name: Cornelius Fiddlebone
  email: cornelius@thewhip.com
  bio: "I ordered what?"
  avatar: bio-photo.jpg
  twitter: rhymeswithsackit
  google:
    plus: CorneliusFiddlebone
{% endhighlight %}

To assign Billy Rick as an author for our post. You'd add the following YAML front matter to a post:

{% highlight yaml %}
author: billy_rick
{% endhighlight %}
