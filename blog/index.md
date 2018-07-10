---
layout: flat
title: Blog Posts
---
# All Posts:
{% for post in site.posts %} {% if post.section == "blog" %}
<div id="display">

h4. "{{post.title}}":{{post.url}} *(light)({{post.date | date_to_string}})*

h5. {{post.subtitle}}
</div>
{% endif %}{% endfor %}
