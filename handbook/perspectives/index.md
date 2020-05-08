---
layout: page
title: Perspectives
---

We put together some theoretical ideas, metaphors and definitions to explain what we mean when we say creative activism.

<div class="card-columns">
    {%- for post in site.categories.perspective -%}
    <div class="card">
        <!--<img src="..." class="card-img-top" alt="...">-->
        <div class="card-body">
        <span>Perspective</span>
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