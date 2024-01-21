---
title: "News"
layout: textlay
excerpt: "Wang Haiying Group at China University of Geosciences &rarr; Beijing."
sitemap: false
permalink: /allnews.html
---

# News

{% for article in site.data.news %}
<p>{{ article.date }} <br> {{ article.headline | markdownify}}</p>
{% endfor %}
