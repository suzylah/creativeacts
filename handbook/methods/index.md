---
layout: page
title: Methods
---

This chapter is a collection of our experiences, introducing creative activism to groups and facilitating a common process. Here you find exercices which can be useful to turn your ideas into actions. The methods are marked according to the level of experience, time and size of the group.

<div class="card-columns">
    {%- for post in site.categories.method -%}
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