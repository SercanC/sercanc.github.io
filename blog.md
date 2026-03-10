---
layout: page
title: Articles
permalink: /blog/
---

# Articles & Blog

Thoughts on water resources, data science, and technology.

---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <span class="post-meta">{{ post.date | date: "%B %-d, %Y" }}</span>
      <h3>
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      </h3>
      {% if post.excerpt %}
        <p>{{ post.excerpt | strip_html | truncatewords: 50 }}</p>
      {% endif %}
    </li>
  {% endfor %}
</ul>

{% if site.posts.size == 0 %}
<p><em>No posts yet. Check back soon!</em></p>
{% endif %}

---

## Topics I Write About

- Water resources engineering and modeling
- Data analysis and visualization
- Python programming for engineers
- Machine learning applications in hydrology
- Software development for water professionals

---

*Want to be notified of new posts? Follow me on [LinkedIn](https://www.linkedin.com/in/sceyhan).*
