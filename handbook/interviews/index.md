---
categories: []
layout: book
title: Interviews
created: 1372505985
---
To understand the motivations of some of our favourite activists, we asked them to share some of their personal experiences. Find living examples and inspiration.

<div class="card-columns">
    {%- for post in site.categories.interview -%}
    <div class="card">
        <!--<img src="..." class="card-img-top" alt="...">-->
        <div class="card-body">
        <span>Interview</span>
        <h5 class="card-title">
            <a class="post-link" href="{{ post.url | relative_url }}">
            {{ post.title | escape }}
            </a>
        </h5>
        <p class="card-text">{{ post.excerpt }}</p>
        </div>
    </div>
    {%- endfor -%}
</div>