---
layout: home
permalink: /
image:
  feature: wood-texture-1600x800.jpg
---

<div class="tiles">
{% for post in site.categories.posts limit:4 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->
