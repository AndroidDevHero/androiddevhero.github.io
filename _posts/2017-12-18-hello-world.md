---
layout: post
title: "Hello World"
description: "It is begining..."
thumb_image: "documentation/sample-image.jpg"
tags: [hello, android]
---
I would like to make android world better for everyone of us.

{% highlight java %}
    @Override
    void createAdapter(List<MediaDef> channels) {
        if (Screen.isLandscape(this))
            leftAdapter(channels);
        else
            horizontalAdapter(channels);
    }
{% endhighlight %}

<a href="/assets/images/android.png" 
  	class="fluidbox-trigger">
  <img src="/assets/images/android.png" alt="Sample image" width="100" height="100"/>
</a>
   