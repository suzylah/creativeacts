---
layout: page
title: Magazine
---

{%- if site.categories.magazine.size > 0 -%}
<h2 class="post-list-heading">{{ page.list_title | default: "Issues" }}</h2>
<ul class="post-list">
    {%- for post in site.categories.magazine -%}
    <li>
    {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
    <span class="post-meta">{{ post.date | date: date_format }}</span>
    <h3>
        <a class="post-link" href="{{ post.url | relative_url }}">
        {{ post.title | escape }}
        </a>
    </h3>
    {{ post.excerpt }}
    </li>
    {%- endfor -%}
</ul>
{%- endif -%}
