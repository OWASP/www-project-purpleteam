---
title: Blog
displaytext: Blog
layout:  null
tab: true
order: 2
tags: PurpleTeam
---

<section class="homepage-blog">
  <h2><a href="/www-project-purpleteam{{ site.posts.first.url }}">{{ site.posts.first.title }}</a></h2>
<a><img src="{{ site.posts.first.author_image }}" alt="image"></a>
<p class="author"><a>{{ site.posts.first.author }}</a><span style="color:#7C7C7C">, {{ site.posts.first.date | date: "%B %e, %Y" }}</span></p>
<p>{{ site.posts.first.excerpt }}<a href="/www-project-purpleteam{{ site.posts.first.url }}">...read more</a></p>
</section>
