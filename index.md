---
layout: default
title: Traveling blog
subtitle:
---

Welcome to my travel blog! I'm excited to share with you my first solo travel adventure, as well as my first time traveling abroad to Boston. This trip is sure to be a memorable one, and I'm grateful to have ChatGPT as my trusty travel guide to help me plan my days and come up with ideas of what to do.

Throughout this blog, I will be verifying the output of ChatGPT and documenting how well it suits the needs of a traveler. While ChatGPT will be mainly responsible for writing the blog based on my rough key points, I will also be sharing my own thoughts and experiences along the way.

As the famous movie character Indiana Jones once said, "It's not the years, honey, it's the mileage." And I can't wait to rack up some serious mileage on this trip. From exploring new cities to trying new foods and making unforgettable memories, I'm ready for whatever this adventure has in store for me.

So join me as I set off on this exciting journey and see the world through my eyes. Who knows what we'll discover together? As the legendary movie character Forrest Gump once said, "Life is like a box of chocolates, you never know what you're gonna get."

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
    </li>
  {% endfor %}
</ul>