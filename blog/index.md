---
layout: default
title: "Blog"
---

# Blog 📝

_"Those who do not learn from history are doomed to repeat it." - George Santayana_

<ul class="post-list">
  {% for post in paginator.posts %}
    <li class="post-item">
      <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
      <small>{{ post.date | date: "%d.%m.%Y" }}</small>
      <p>{{ post.excerpt | strip_html | truncate: 180 }}</p>
      <a class="readmore" href="{{ post.url | relative_url }}">Læs mere →</a>
    </li>
  {% endfor %}
</ul>

<nav class="pager">
  {% if paginator.previous_page %}
    <a class="prev" href="{{ paginator.previous_page_path | relative_url }}">← Nyere indlæg</a>
  {% endif %}
  <span class="page-info">Side {{ paginator.page }} af {{ paginator.total_pages }}</span>
  {% if paginator.next_page %}
    <a class="next" href="{{ paginator.next_page_path | relative_url }}">Ældre indlæg →</a>
  {% endif %}
</nav>

<style>
.post-list{list-style:none;margin:0;padding:0;display:grid;gap:1.1rem}
.post-item{background:rgba(255,255,255,.04);border:1px solid rgba(255,255,255,.07);border-radius:.5rem;padding:.9rem}
.post-item h3{margin:.1rem 0 .2rem}
.post-item .readmore{font-weight:600;text-decoration:none}
.pager{display:flex;align-items:center;justify-content:space-between;margin:1.2rem 0 .4rem}
.pager .page-info{opacity:.8}
</style>
