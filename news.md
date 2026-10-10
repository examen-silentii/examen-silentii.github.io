---
layout: page
title: News
permalink: /news/
---

<ul class="news-list">
{%- for post in site.posts -%}
  <li>
    <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%-d %B %Y" }}</time>
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{%- endfor -%}
</ul>

News is also available as a [feed]({{ '/feed.xml' | relative_url }}).
