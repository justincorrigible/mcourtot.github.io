---
title: News
nav:
  order: 6
  tooltip: News, musings and miscellany
---

# {% include icon.html icon="fa-solid fa-feather-pointed" %}News

{% include search-box.html %}

{% include tags.html tags=site.tags %}

{% include search-info.html %}

{% include list.html data="posts" component="post-excerpt" %}
