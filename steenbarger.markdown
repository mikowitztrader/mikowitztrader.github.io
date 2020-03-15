---
layout: page
title: The Daily Trading Coach
permalink: /steenbarger/
---

The posts listed on this page comprise an in-progress series of blog posts commenting on the lessons provided by Dr. Brett Steenbarger in his book
[The Daily Trading Coach: 101 Lessons for Becoming Your Own Trading Psychologist](https://amzn.to/2I9rlMQ). New posts will be added to the list below as I publish them.

These posts are not meant as a substitute for reading Dr. Brett's book yourself. Each lesson touches on many topics, and while I try to address them all,
in each post I focus on what I found most personally meaningful in each lesson. If you find value in any of my posts, I strongly suggest you purchase your
own copy of the book using the link at the bottom of the page

{% assign steen_posts = site.posts | sort: 'lesson', 'last' %}

<ul>
{% for post in steen_posts %}
  {% if post.url contains 'steenbarger' %}
    <li><a class="page-link" href="{{ post.url | prepend: site.baseurl }}">Lesson {{post.lesson}} - {{post.subtitle}}</a></li>
  {% endif %}
{% endfor %}
</ul>

---
<br />

<iframe style="width:120px;height:240px;" marginwidth="0" marginheight="0" scrolling="no" frameborder="0" src="//ws-na.amazon-adsystem.com/widgets/q?ServiceVersion=20070822&OneJS=1&Operation=GetAdHtml&MarketPlace=US&source=ss&ref=as_ss_li_til&ad_type=product_link&tracking_id=mikowitz-20&language=en_US&marketplace=amazon&region=US&placement=B0023SDQRG&asins=B0023SDQRG&linkId=a64be8fb6e543c28f76e57c55530c46e&show_border=true&link_opens_in_new_window=true"></iframe>

