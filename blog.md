---
title: Blog
permalink: /blog
breadcrumb: Blog
featured_image: /assets/images/bg.jpg
---

<div class="grid-container">
  {% for post in site.posts %}
      {% include card.html url=post.url img_url=post.featured_image title=post.title description=post.content %}
  {% endfor %}
</div>