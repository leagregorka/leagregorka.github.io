---
title: Blog
permalink: /blog
breadcrumb: Blog
featured_image: /assets/images/blog_bg.jpg
featured_title: Blog
---

<div class="grid-container">
  {% for post in site.posts %}
      {% include card.html url=post.url img_url=post.featured_image title=post.title description=post.excerpt %}
  {% endfor %}
</div>