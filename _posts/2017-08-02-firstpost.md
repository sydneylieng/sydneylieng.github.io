---
layout: post
title:  "First Post: All about me!"
date:   2017-08-02
excerpt: "All you need to know."
tag:

---

{% capture fig_img %}
![Foo]({{ site.url }}/images/pageone2.jpg)
{% endcapture %}

<figure>
  {{ fig_img | markdownify | remove: "<p>" | remove: "</p>" }}
  <figcaption>This is me.</figcaption>
</figure>

<iframe src="https://ghbtns.com/github-btn.html?user=TaylanTatli&repo=Halve&type=star&count=true&size=large" frameborder="0" scrolling="0" width="160px" height="30px"></iframe>    
      
